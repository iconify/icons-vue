<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="stzivqfiq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:text-select-move-forward-word-sharp" /></template>
<style>
.stzivqfiq {
  fill: currentColor;
  d: path("m16.712 15.289l-.708-.689l2.075-2.1H11v-1h7.079l-2.075-2.1l.707-.688L20 12zM4 20V4h4.923v16zm7.385 0v-1.23h1.23V20zm0-14.77V4h1.23v1.23zM15.077 20v-1.23h1.23V20zm0-14.77V4h1.23v1.23zM18.769 20v-1.23H20V20zm0-14.77V4H20v1.23z");
}

</style>
