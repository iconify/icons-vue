<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exrqpttnt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:play-pass-outline" /></template>
<style>
.exrqpttnt {
  fill: currentColor;
  d: path("M12 20q-.825 0-1.413.588T10 22H7q-.825 0-1.413-.588T5 20V4q0-.825.588-1.413T7 2h3q0 .825.588 1.413T12 4q.825 0 1.413-.588T14 2h3q.825 0 1.413.588T19 4v16q0 .825-.588 1.413T17 22h-3q0-.825-.588-1.413T12 20Zm0-2q1.075 0 1.988.537T15.45 20H17V4h-1.55q-.55.925-1.463 1.463T12 6q-1.075 0-1.988-.537T8.55 4H7v16h1.55q.55-.925 1.463-1.463T12 18Zm0-6Z");
}

</style>
