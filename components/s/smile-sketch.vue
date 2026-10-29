<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yttz3kdvz.css';
import '../../css/e/eo7h87buu.css';
import '../../css/n/nlw4k8bvo.css';
import '../../css/n/nnyd2wbkl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="yttz3kdvz"/><path class="eo7h87buu wm-a"/><path class="nlw4k8bvo wm-k"/><path class="nnyd2wbkl wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:smile-sketch" /></template>
