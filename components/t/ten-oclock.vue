<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="yqfvb1bwf"/><circle class="f934iu1fb"/><path class="mbt1d-r9l"/><path class="th4vr_ono"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:ten-oclock" /></template>
<style>
.f934iu1fb {
  cx: 18px;
  cy: 18px;
  r: 14px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

.mbt1d-r9l {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M17 18a1 1 0 1 0 2 0V7a1 1 0 1 0-2 0z");
}

.th4vr_ono {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M9.339 13a1 1 0 0 0 .366 1.366l7.795 4.5a1 1 0 0 0 1-1.732l-7.795-4.5A1 1 0 0 0 9.339 13");
}

.yqfvb1bwf {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--99aab5, #99aab5);
}

</style>
