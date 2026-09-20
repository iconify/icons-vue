<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nlizunuhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:wrist-sharp" /></template>
<style>
.nlizunuhb {
  fill: currentColor;
  d: path("M11.192 20.708L6.485 16H1.692V8h4.293l1.988-2h11.335v1h-5v2.173h7v1h-7v2.154h8v1h-8V15.5h6v1H11.51l1.279 2.533z");
}

</style>
