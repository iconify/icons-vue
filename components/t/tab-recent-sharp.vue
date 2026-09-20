<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxrrthffh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-recent-sharp" /></template>
<style>
.xxrrthffh {
  fill: currentColor;
  d: path("m19.65 20.35l.7-.7l-1.85-1.85V15h-1v3.2zM13 10h7V6h-7zm1.463 11.538Q13 20.075 13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23t-3.537-1.463M2 20V4h20v8.275q-.875-.625-1.912-.95T17.975 11q-2.9 0-4.937 2.05T11 18q0 .525.075 1.025T11.3 20z");
}

</style>
