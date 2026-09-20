<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t45w0t3ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:pols" /></template>
<style>
.t45w0t3ls {
  fill: var(--svg-color--ff3364, #ff3364);
  fill-rule: evenodd;
  d: path("M7.065 3h7.25A6.68 6.68 0 0 1 21 9.677a6.68 6.68 0 0 1-6.684 6.678H11.71V21H7.065v-2.392a4.494 4.494 0 0 0 3.344-4.358a4.496 4.496 0 0 0-3.344-4.358zm4.645 3.484h2.699c1.716 0 3.107 1.43 3.107 3.193c0 1.765-1.391 3.194-3.107 3.194h-2.7zM5.903 17.226a2.904 2.904 0 1 0 0-5.808a2.904 2.904 0 0 0 0 5.808");
}

</style>
