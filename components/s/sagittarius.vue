<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dgh7jhswh"/><path class="x56n5pb0i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:sagittarius" /></template>
<style>
.dgh7jhswh {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.x56n5pb0i {
  fill: var(--svg-color--fff, #fff);
  d: path("M28.5 6H17a1.5 1.5 0 1 0 0 3h7.879L13 20.879L9.061 16.94a1.5 1.5 0 1 0-2.121 2.121L10.879 23L5.94 27.94a1.5 1.5 0 1 0 2.121 2.12L13 25.121l3.94 3.939a1.496 1.496 0 0 0 2.12 0a1.5 1.5 0 0 0 0-2.121L15.121 23L27 11.121V19a1.5 1.5 0 0 0 3 0V7.5A1.5 1.5 0 0 0 28.5 6");
}

</style>
