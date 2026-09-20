<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="dgh7jhswh"/><path class="xsgfndb9c"/><circle class="fdwkxbc3i"/><circle class="fbyw32bzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:yin-yang" /></template>
<style>
.dgh7jhswh {
  fill: var(--svg-color--9266cc, #9266cc);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.fbyw32bzx {
  cx: 18px;
  cy: 12px;
  r: 2.5px;
  fill: var(--svg-color--9266cc, #9266cc);
}

.fdwkxbc3i {
  cx: 18px;
  cy: 24px;
  r: 2.5px;
  fill: var(--svg-color--fff, #fff);
}

.xsgfndb9c {
  fill: var(--svg-color--fff, #fff);
  d: path("M18.964 4.033C11.251 3.501 4.566 9.322 4.033 17.036s5.289 14.399 13.002 14.931c7.714.533 14.399-5.289 14.931-13.002c.533-7.714-5.288-14.399-13.002-14.932m-1.183 25.983A6.01 6.01 0 0 1 18 18a6.01 6.01 0 0 0 6.118-5.897c.046-2.558-1.524-4.748-3.758-5.657l.151-.171c5.517 1.174 9.612 6.096 9.506 11.943c-.122 6.639-5.597 11.919-12.236 11.798");
}

</style>
