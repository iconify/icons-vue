<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="pl2xwzbmx"/><path class="br5go2bpx"/><path class="k0079abqj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:womans-clothes" /></template>
<style>
.br5go2bpx {
  fill: var(--svg-color--aa8dd8, #aa8dd8);
  d: path("M30.559 16.823L35 11c-4-2-11-8-11-8s-2 4-6 4s-6-4-6-4s-7 6-11 8l4.439 5.824L10 15s.25 16-3 19c0 0 5 1 11 1s11-1 11-1c-3.25-3-3-19-3-19z");
}

.k0079abqj {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M6 17a1 1 0 0 1-.781-.375l-4-5a1 1 0 1 1 1.561-1.249l4 5A1 1 0 0 1 6 17m23.999 0a1 1 0 0 1-.78-1.624l4-5a1 1 0 0 1 1.562 1.249l-4 5a1 1 0 0 1-.782.375M24 3s-3 3-6 3s-6-3-6-3l2 7l3-2.25V34a1 1 0 1 0 2 0V7.75L22 10z");
}

.pl2xwzbmx {
  fill: var(--svg-color--553788, #553788);
  d: path("M12 3h12s-1 3-6 3s-6-3-6-3");
}

</style>
