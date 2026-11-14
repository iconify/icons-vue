<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fdcewub2r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shield-heart" /></template>
<style>
.fdcewub2r {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.758 4.796l-7.5-2.75Q12.133 2 12 2t-.258.046l-7.5 2.75q-.108.04-.2.11q-.091.07-.157.165q-.066.094-.1.204q-.035.11-.035.225v6q0 7.276 7.973 10.447q.133.053.277.053t.277-.053Q20.25 18.776 20.25 11.5v-6q0-.115-.035-.225q-.034-.11-.1-.204q-.066-.095-.157-.165q-.092-.07-.2-.11m-8.155 11.34Q7.25 13.416 7.25 10.25q0-3.25 3-3.25q1.034 0 1.75.601Q12.716 7 13.75 7q3 0 3 3.25q0 3.166-4.353 5.886q-.089.056-.19.085T12 16.25q-.105 0-.207-.029t-.19-.085");
}

</style>
