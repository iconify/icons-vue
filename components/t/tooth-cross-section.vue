<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5lklutec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:tooth-cross-section" /></template>
<style>
.t5lklutec {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M9.788 2.933Q8.15 2.25 7 2.25q-4.25 0-4.25 5.25q0 2.091 1.262 4.767q.593 1.255.757 1.901l1.247 5.985q.307 1.535 1.734 1.535q1.414 0 1.73-1.512l1.237-4.454q.212-.597 1.283-.597t1.283.597l1.237 4.454q.316 1.512 1.73 1.512q1.427 0 1.735-1.541l1.246-5.979q.164-.646.757-1.901Q21.25 9.591 21.25 7.5q0-5.25-4.25-5.25q-1.15 0-2.788.683Q12.85 3.5 12 3.5t-2.212-.567M7.25 11V8.5q0-1.583 1.087-2.036q.984-.41 2.113.436L12 8.063L13.55 6.9q1.129-.846 2.113-.436q1.087.453 1.087 2.036V11q0 1.75-2 1.75h-5.5q-2 0-2-1.75");
}

</style>
