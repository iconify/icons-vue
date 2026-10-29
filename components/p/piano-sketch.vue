<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tczw_hbsg.css';
import '../../css/r/r-bsq-m3v.css';
import '../../css/k/kqraa7qvj.css';
import '../../css/r/r0m-rx3lk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="r-bsq-m3v wm-k"/><path class="kqraa7qvj wm-k"/><path class="r0m-rx3lk wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:piano-sketch" /></template>
