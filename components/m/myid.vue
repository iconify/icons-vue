<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a13mkh37s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myid" /></template>
<style>
.a13mkh37s {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m41.98 18.143l-3.918-6.786l-10.144 5.857V5.5h-7.836v11.714L9.938 11.357L6.02 18.143L16.164 24L6.02 29.857l3.918 6.786l10.144-5.857V42.5h7.836V30.786l10.144 5.857l3.918-6.786L31.836 24z");
}

</style>
