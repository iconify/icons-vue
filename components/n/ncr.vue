<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGntUqGdWQ)" class="t6uxs-b_l"/><path fill="url(#SVGuSQmocNr)" clip-rule="evenodd" class="ly8w8t0um"/><defs><linearGradient id="SVGntUqGdWQ" x1="18.617" x2="5.382" y1="5.383" y2="18.354" gradientUnits="userSpaceOnUse"><stop class="eiaaj5b6m"/><stop offset=".53" class="dl2ggdbks"/><stop offset="1" class="ylekb4bkl"/></linearGradient><linearGradient id="SVGuSQmocNr" x1="18.618" x2="5.382" y1="5.382" y2="18.353" gradientUnits="userSpaceOnUse"><stop class="eiaaj5b6m"/><stop offset=".53" class="dl2ggdbks"/><stop offset="1" class="ylekb4bkl"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ncr" /></template>
<style>
.dl2ggdbks {
  stop-color: var(--svg-color--f4b86d, #f4b86d);
}

.eiaaj5b6m {
  stop-color: var(--svg-color--f58f05, #f58f05);
}

.ft5dv1b6b {
  fill: none;
}

.ly8w8t0um {
  fill-rule: evenodd;
  d: path("M18.364 5.636A9 9 0 1 0 5.636 18.364A9 9 0 0 0 18.364 5.636m-.673.064a8.58 8.58 0 0 0-5.69-2.17A8.58 8.58 0 0 0 6.308 5.7l.397.397a7.9 7.9 0 0 1 10.599-.01zm2.234 5.77a7.9 7.9 0 0 0-1.974-4.732l.35-.387a8.95 8.95 0 0 1 2.17 5.12zm-1.995 5.808A7.9 7.9 0 0 0 19.94 12h.53c0 2.012-.826 4.167-2.17 5.649zm-11.235.636A7.9 7.9 0 0 0 12 19.94a7.93 7.93 0 0 0 5.305-2.027l.386.386a8.5 8.5 0 0 1-5.69 2.17a8.58 8.58 0 0 1-5.692-2.17zM4.06 12c0 2.017.752 3.865 1.99 5.262l-.349.387A9 9 0 0 1 3.53 12zm2.038-5.294a7.92 7.92 0 0 0-2.022 4.765H3.53c.132-1.911.953-3.812 2.17-5.162zm1.668 10.588V7.235h2.954l4.987 9.094V7.235h.53v10.06H13.28L8.294 8.2v9.093z");
}

.t6uxs-b_l {
  d: path("M13.588 16.766h1.853l-5.024-9H8.559z");
}

.ylekb4bkl {
  stop-color: var(--svg-color--ea911d, #ea911d);
}

</style>
