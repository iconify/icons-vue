<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="yqfvb1bwf"/><circle class="f934iu1fb"/><path class="gy_izpc4f"/><path class="zgr6_winf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:twelve-thirty" /></template>
<style>
.f934iu1fb {
  cx: 18px;
  cy: 18px;
  r: 14px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

.gy_izpc4f {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M17 18a1 1 0 1 1 2 0v11a1 1 0 0 1-2 0z");
}

.yqfvb1bwf {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--99aab5, #99aab5);
}

.zgr6_winf {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M19 18a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0z");
}

</style>
