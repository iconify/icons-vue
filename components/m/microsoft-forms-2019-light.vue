<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y_ttfbbvt.css';
import '../../css/j/j29g_4b6w.css';
import '../../css/n/nzpzadcnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="y_ttfbbvt"/><path class="j29g_4b6w"/><path class="nzpzadcnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:microsoft-forms-2019-light" /></template>
