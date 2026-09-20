<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c1ckw1b2l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:work-update-sharp" /></template>
<style>
.c1ckw1b2l {
  fill: currentColor;
  d: path("m18 20.596l2.539-2.538l-.547-.546l-1.608 1.607v-3.715h-.769v3.715l-1.607-1.607l-.547.546zM10 7h4V5h-4zm5.165 13.836Q14 19.67 14 18t1.165-2.835T18 14t2.836 1.165T22 18t-1.164 2.836T18 22t-2.835-1.164M3 20V7h6V4h6v3h6v5.814q-.683-.414-1.448-.614T18 12q-2.496 0-4.248 1.752T12 18q0 .506.086 1.009t.262.991z");
}

</style>
