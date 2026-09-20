<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="kz-tx6bwo"/><path class="u3yqph0tw"/><path class="b-2-7pyyg"/><path class="pj_ijbcni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:probing-cane" /></template>
<style>
.b-2-7pyyg {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M24.812 8.754a.904.904 0 0 1 0-1.275l3.825-3.825a.904.904 0 0 1 1.275 0a.904.904 0 0 1 0 1.275l-3.825 3.825a.904.904 0 0 1-1.275 0");
}

.kz-tx6bwo {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m25.45 6.842l1.274 1.274L7.6 27.241l-1.275-1.275zM.587 32.979a.904.904 0 0 1 0-1.275l3.825-3.825a.904.904 0 0 1 1.275 0a.904.904 0 0 1 0 1.275l-3.825 3.825a.905.905 0 0 1-1.275 0");
}

.pj_ijbcni {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M25.606 9.548L24.018 7.96a.5.5 0 0 1 0-.707l.568-.568a.5.5 0 0 1 .707 0l1.588 1.588a.5.5 0 0 1 0 .707l-.568.568a.5.5 0 0 1-.707 0m6.924-3.259c-1.527-.215-3.042-1.485-3.114-1.545l-.328-.278l.261-.34c1.04-1.354 3.855-1.973 5.366-1.189c1.138.591 1.179 1.318 1.103 1.698c-.175.872-1.263 1.561-2.648 1.677q-.316.023-.64-.023M30.382 4.35c.664.474 1.815 1.134 2.713 1.062c1.002-.084 1.76-.562 1.839-.955c.064-.321-.423-.612-.635-.721c-1.021-.534-2.947-.189-3.917.614");
}

.u3yqph0tw {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("m7.599 24.691l1.275 1.275l-5.1 5.1L2.5 29.79z");
}

</style>
