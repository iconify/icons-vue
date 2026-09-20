<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="drdd56bfh"><path clip-rule="evenodd" class="gnq9prb6g"/><path class="lh5eq1bnz"/><path class="igaculbht"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:sc" /></template>
<style>
.drdd56bfh {
  fill: var(--svg-color--15d47b, #15d47b);
}

.gnq9prb6g {
  fill-rule: evenodd;
  d: path("M14.813 14.813V12A2.813 2.813 0 1 0 12 14.813zM12 6.937a5.062 5.062 0 1 0 0 10.125h4.5a.56.56 0 0 0 .563-.562V12A5.06 5.06 0 0 0 12 6.938");
}

.igaculbht {
  d: path("M6.094 7.5a1.406 1.406 0 1 0 0-2.813a1.406 1.406 0 0 0 0 2.813");
}

.lh5eq1bnz {
  d: path("M12 3.563a8.438 8.438 0 1 0 0 16.875a8.438 8.438 0 0 0 0-16.875M3 12a9 9 0 0 1 9-9a9 9 0 0 1 9 9a9 9 0 0 1-9 9a9 9 0 0 1-9-9");
}

</style>
