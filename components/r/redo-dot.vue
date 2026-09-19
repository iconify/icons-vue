<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hntgybcog.css';
import '../../css/s/suw67z4bs.css';
import '../../css/p/plbg7nf0v.css';
import '../../css/r/r71_f-bif.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="suw67z4bs"/><path class="plbg7nf0v"/><path class="r71_f-bif"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:redo-dot" /></template>
