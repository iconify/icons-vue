<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="symq3hbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:priority-high-sharp" /></template>
<style>
.symq3hbge {
  fill: currentColor;
  d: path("M12 18.846q-.413 0-.706-.293T11 17.846t.294-.706t.706-.294t.706.294t.294.706t-.294.707t-.706.293m-.73-3.807V4.154h1.46v10.885z");
}

</style>
