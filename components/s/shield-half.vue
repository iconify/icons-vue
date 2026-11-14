<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjnw-fbrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:shield-half" /></template>
<style>
.bjnw-fbrz {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m19.758 4.796l-7.5-2.75q.108.04.2.11q.091.07.157.165q.066.094.1.204q.035.11.035.225v18.5q0 .113-.033.22q-.033.108-.096.201q-.064.093-.151.164q-.088.07-.193.112Q20.25 18.776 20.25 11.5v-6q0-.115-.035-.225q-.034-.11-.1-.204q-.066-.095-.157-.165q-.092-.07-.2-.11m-8.035 17.151q-.105-.042-.193-.112q-.087-.071-.151-.164q-.063-.093-.096-.201q-.033-.107-.033-.22V2.75q0-.115.035-.225q.034-.11.1-.204q.066-.095.157-.165q.092-.07.2-.11l-7.5 2.75q-.108.04-.2.11q-.091.07-.157.165q-.066.094-.1.204q-.035.11-.035.225v6q0 7.276 7.973 10.447");
}

</style>
