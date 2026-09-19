<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jx0p4fbya.css';
import '../../css/o/omv99sb0f.css';
import '../../css/q/qxcdtgl1w.css';
import '../../css/w/wttawfb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="omv99sb0f"/><path class="qxcdtgl1w"/><path class="wttawfb0l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:tablet-connected-bluetooth" /></template>
