<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sjltxzbrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:tab-recent-outline-sharp" /></template>
<style>
.sjltxzbrh {
  fill: currentColor;
  d: path("M14.463 21.538Q13 20.075 13 18t1.463-3.537T18 13t3.538 1.463T23 18t-1.463 3.538T18 23t-3.537-1.463m5.187-1.187l.7-.7l-1.85-1.85V15h-1v3.2zM13 10h7v1.3q.55.175 1.05.413t.95.562V4H2v16h9.3q-.15-.475-.225-.975T11 18H4V6h9zm-9 8V6z");
}

</style>
