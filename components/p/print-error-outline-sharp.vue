<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr0jxob7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:print-error-outline-sharp" /></template>
<style>
.vr0jxob7g {
  fill: currentColor;
  d: path("M7 20v-4H3.577V8.616h16.556v1H4.577V15H7v-1.538h9.116v1H8V19h8.116v1zM7 8.615v-4h10v4h-1v-3H8v3zM18.48 19.79q-.21-.21-.21-.52t.21-.521q.209-.21.52-.21t.52.21t.21.52t-.21.52Q19.312 20 19 20t-.52-.21m.02-4.02v-4h1v4zM4.577 9.615h15.556z");
}

</style>
