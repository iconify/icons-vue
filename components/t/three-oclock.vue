<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="yqfvb1bwf"/><circle class="f934iu1fb"/><path class="y_ptlabie"/><path class="id9ecjb3h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:three-oclock" /></template>
<style>
.f934iu1fb {
  cx: 18px;
  cy: 18px;
  r: 14px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

.id9ecjb3h {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M28 18a1 1 0 0 1-1 1h-9a1 1 0 0 1 0-2h9a1 1 0 0 1 1 1");
}

.y_ptlabie {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M19 18a1 1 0 1 1-2 0V7a1 1 0 0 1 2 0z");
}

.yqfvb1bwf {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--99aab5, #99aab5);
}

</style>
