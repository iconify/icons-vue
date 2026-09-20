<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="grif-4vgr"/><g class="mrppgkbbg"><path class="gz8zvif8u"/><path class="c612-ccav"/></g><path class="oy2-340ig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:swim-brief" /></template>
<style>
.c612-ccav {
  d: path("M36 10H.052V8.199c0-.735.596-1.331 1.331-1.331h33.286c.735 0 1.331.596 1.331 1.331z");
}

.grif-4vgr {
  fill: var(--svg-color--2976aa, #2976aa);
  d: path("M36 17.96V10l-8.296-2H8.348L.052 10v7.96C.052 21.426 12.376 32 14.835 32h6.382C23.4 32 36 21.715 36 17.96");
}

.gz8zvif8u {
  d: path("m4.617 18.577l-1.892-.647C4 14.201 4 10.904 4 9.32h2c0 1.692 0 5.213-1.383 9.257m26.818.152C30 14.622 30 11.041 30 9.32h2c0 1.611 0 4.963 1.323 8.75z");
}

.mrppgkbbg {
  fill: var(--svg-color--5dadec, #5dadec);
}

.oy2-340ig {
  fill: var(--svg-color--1d567c, #1d567c);
  d: path("m3.702 18.154l-.03.099c.011-.033.018-.065.03-.099c-1.464-.547-2.75-.865-3.649-1.019v.825C.052 21.426 12.409 32 14.854 32h.934c-1.155-8.143-7.473-12.122-12.086-13.846M36 17.96v-.747c-.897.147-2.196.459-3.677 1.005c.021.061.035.12.057.181c-.021-.061-.036-.12-.057-.181c-4.6 1.696-10.905 5.635-12.059 13.782h.934C23.369 32 36 21.715 36 17.96");
}

</style>
