<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ifxa1tbxv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:window-horizontal-sharp-fill" /></template>
<style>
.ifxa1tbxv {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M21 4C21.552 4 22 4.448 22 5V18H23V20H1V18H2V5C2 4.448 2.448 4 3 4H21ZM11 6V11H4V13H11V18H13V13H20V11H13V6H11Z");
}

</style>
