<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g-tqdrbyb"/><path clip-rule="evenodd" class="j-tmtc6ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:minimalistic-magnifer-bold-duotone" /></template>
<style>
.g-tqdrbyb {
  fill: currentColor;
  d: path("M20.313 11.157a9.157 9.157 0 1 1-18.313 0a9.157 9.157 0 0 1 18.313 0");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.j-tmtc6ls {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M18.839 18.839a.723.723 0 0 1 1.022 0l1.928 1.927a.723.723 0 0 1-1.023 1.023L18.84 19.86a.723.723 0 0 1 0-1.022");
}

</style>
