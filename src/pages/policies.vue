<template>
  <center>
    <div id="policies" style="min-height: 200vh" class="q-ma-lg">
      <q-card flat bordered class="my-card bg-grey-1">
        <q-card-section>
          <div class="row items-center no-wrap">
            <div class="col">
              <div class="text-h5">회원약관</div>
              <br />
              <q-field standout :dense="dense" disable readonly>
                <template v-slot:control>
                  <div class="self-center full-width no-outline">
                    {{
                      "약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용 약관내용"
                    }}
                  </div>
                </template>
              </q-field>
              <br />
              <br />
              <q-btn unelevated color="black" label="확인" to="/signUp"></q-btn>
            </div>
          </div>
        </q-card-section>
      </q-card>
    </div>
  </center>
</template>

<script>
import { defineComponent, ref } from "vue";

export default defineComponent({
  name: "PageIndex",
  setup() {
    return {
      text: ref("Field content"),
      dense: ref(false),
    };
  },
});
</script>

<style lang="scss">
.policies {
  display: flex;
  width: 50%;
  justify-content: center;
  // max-width: 250px
  align-items: center;
}
</style>
