<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dgh7jhswh"/><path class="d7ph-yb-b"/><path class="ya59wci_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:ophiuchus" /></template>
<style>
.d7ph-yb-b {
  fill: var(--svg-color--fff, #fff);
  d: path("M18 30.5c-5.526 0-8-4.27-8-8.5V7a1.5 1.5 0 1 1 3 0v15c0 1.29.36 5.5 5 5.5s5-4.21 5-5.5V7a1.5 1.5 0 1 1 3 0v15c0 4.23-2.474 8.5-8 8.5");
}

.dgh7jhswh {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.ya59wci_r {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 21.5a1.5 1.5 0 0 1-1.061-2.561c.525-.525.987-1.019 1.414-1.475C6.428 15.25 8.066 13.5 12 13.5c2.43 0 4.649 1.387 6.795 2.728C20.664 17.396 22.431 18.5 24 18.5c2.633 0 3.518-.945 5.457-3.015c.447-.479.933-.996 1.483-1.545a1.5 1.5 0 1 1 2.121 2.121c-.524.525-.986 1.019-1.414 1.475C29.572 19.751 27.934 21.5 24 21.5c-2.431 0-4.649-1.387-6.795-2.728C15.335 17.604 13.57 16.5 12 16.5c-2.633 0-3.518.945-5.457 3.015c-.448.479-.933.996-1.483 1.546A1.5 1.5 0 0 1 4 21.5");
}

</style>
