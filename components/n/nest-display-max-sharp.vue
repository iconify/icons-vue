<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wbpvt56yz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:nest-display-max-sharp" /></template>
<style>
.wbpvt56yz {
  fill: currentColor;
  d: path("M12.54 9.54q.23-.23.23-.54t-.23-.54t-.54-.23t-.54.23t-.23.54t.23.54t.54.23t.54-.23M12 18.5q-2.436 0-3.968-.29q-1.532-.289-1.532-.744V16.5H4.29q-.702 0-1.186-.525q-.485-.525-.429-1.227l.656-7.77q.05-.62.519-1.05q.47-.428 1.096-.428h14.108q.627 0 1.096.429t.52 1.05l.655 7.769q.056.702-.429 1.227q-.484.525-1.186.525H17.5v.966q0 .455-1.532.744q-1.531.29-3.968.29");
}

</style>
