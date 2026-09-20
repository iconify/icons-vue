<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uz_jp4v5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:movie-edit-off-outline-sharp" /></template>
<style>
.uz_jp4v5f {
  fill: currentColor;
  d: path("M3 19V5h1.808l4 4H4v9h7.846v1zM21 5v4h-9.361l-4-4H9.05l1.433 2.844l.156.156h2.919l-1.5-3h2.5l1.5 3h3l-1.5-3zm.116 9.06l-.925-.945zm-1.564 2.828l-2.21-2.184l2.849-2.848l2.19 2.203zm-4.437 2.227h.95l.716-.715l-.95-.95l-.715.716zm6.258 2.45l-.714.714l-3.246-3.252l-.973.973h-2.21v-2.21l.974-.967L1.72 3.341l.714-.714z");
}

</style>
