<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="sh9s8dbxs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-paragraph-20-filled" /></template>
<style>
.sh9s8dbxs {
  fill: currentColor;
  d: path("M13.5 7a3.5 3.5 0 1 0 0 7h.5v3.5a.5.5 0 0 0 1 0V8h1v9.5a.5.5 0 0 0 1 0V8h.5a.5.5 0 0 0 0-1zm-11-2a.5.5 0 0 0 0 1h15a.5.5 0 0 0 0-1zm6.756 4H2.5a.5.5 0 0 0 0 1h6.527q.06-.522.23-1m.502 4H2.5a.5.5 0 0 0 0 1h8.171a4.5 4.5 0 0 1-.913-1");
}

</style>
