<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="utth0edqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:phone-cancel-outline" /></template>
<style>
.utth0edqx {
  fill: currentColor;
  d: path("M18.93 20q-2.528 0-5.184-1.266t-4.935-3.555t-3.545-4.935T4 5.07q0-.458.3-.763T5.05 4h2.473q.403 0 .719.257t.404.659L9.142 7.3q.07.42-.025.733t-.333.513L6.59 10.592q.616 1.117 1.361 2.076t1.59 1.817q.87.87 1.874 1.62q1.004.749 2.204 1.414l2.139-2.177q.244-.263.549-.357t.674-.023l2.103.43q.408.095.662.408t.254.715v2.435q0 .45-.306.75t-.763.3M6.12 9.654l1.92-1.765q.095-.077.124-.212q.03-.135-.01-.25l-.443-2.12q-.039-.153-.135-.23T7.327 5H5.275q-.115 0-.192.077t-.077.192q.029 1.025.321 2.14t.794 2.245m8.45 8.334q1.014.502 2.16.743q1.148.24 2 .257q.115 0 .192-.077T19 18.72v-2.008q0-.153-.077-.25q-.077-.096-.23-.134l-1.85-.379q-.116-.039-.203-.01q-.086.03-.182.125zm.54-8.392l-.707-.708l2.094-2.1l-2.094-2.075l.708-.713l2.1 2.1L19.287 4l.713.713l-2.08 2.076l2.08 2.1l-.713.707l-2.075-2.075z");
}

</style>
