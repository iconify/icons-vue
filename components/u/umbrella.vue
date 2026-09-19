<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="s7-kg40sd"/><path class="r45rdvbvd"/><path class="b5rswxbll"/><path class="ll11kcb9a"/><path class="e-vjyacow"/><path class="pg-nvglvw"/><path class="klby_lust"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:umbrella" /></template>
<style>
.b5rswxbll {
  fill: var(--svg-color--ffbe5c, #ffbe5c);
  d: path("M32 6.7v24.4c1.8-2.3 4.5-3.8 7.7-3.8c3.1 0 5.9 1.5 7.7 3.8C45.9 17.3 39.7 6.7 32 6.7");
}

.e-vjyacow {
  fill: var(--svg-color--c7e86f, #c7e86f);
  d: path("M32 6.7c7.7 0 13.9 10.6 15.4 24.4c1.8-2.3 4.5-3.8 7.7-3.8c2.7 0 5.2 1.1 7 2.9C59 16.8 46.7 6.7 32 6.7");
}

.klby_lust {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M30.1 48.9v5.6c0 2.1-1.7 3.8-3.8 3.8s-3.8-1.7-3.8-3.8c0-1-.8-1.9-1.9-1.9s-1.9.8-1.9 1.9c0 4.1 3.4 7.5 7.5 7.5s7.5-3.4 7.5-7.5v-5.6z");
}

.ll11kcb9a {
  fill: var(--svg-color--ed77a8, #ed77a8);
  d: path("M32 6.7v24.4c-1.8-2.3-4.5-3.8-7.7-3.8s-5.9 1.5-7.7 3.8C18.1 17.3 24.3 6.7 32 6.7");
}

.pg-nvglvw {
  fill: var(--svg-color--60d4e0, #60d4e0);
  d: path("M32 6.7c-7.7 0-13.9 10.6-15.4 24.4c-1.8-2.3-4.5-3.8-7.7-3.8c-2.7 0-5.2 1.1-7 2.9C5 16.8 17.3 6.7 32 6.7");
}

.r45rdvbvd {
  fill: var(--svg-color--b8c2c4, #b8c2c4);
  d: path("M31.1 24.5H33v24.4h-1.9z");
}

.s7-kg40sd {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M32 2c-.5 0-.9.4-.9.9v4.7H33V2.9c-.1-.5-.5-.9-1-.9");
}

</style>
