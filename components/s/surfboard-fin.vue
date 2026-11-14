<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w62qvacgx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:surfboard-fin" /></template>
<style>
.w62qvacgx {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M2.815 8.036Q1.75 8.645 1.75 10q0 3.19 3.131 3.249q.968 4.398 4.84 5.947q.069.028.142.041t.146.013q.074-.001.146-.016q.073-.016.14-.045t.129-.071t.113-.094t.092-.115q.04-.062.067-.13q.09-.226.032-.461q-.696-2.782.32-5.426q8.793-1.165 10.654-6.129q.055-.146.047-.302q-.008-.157-.078-.296q-.033-.066-.079-.125q-.045-.058-.101-.107q-.055-.048-.12-.085q-.064-.036-.134-.06q-.07-.023-.143-.032t-.147-.004t-.145.025t-.137.052Q13.883 9.22 5.123 7.76q-1.412-.235-2.308.276m6.182 9.09q-1.913-1.307-2.577-3.893q1.567-.038 2.979-.161q-.613 1.994-.402 4.054");
}

</style>
