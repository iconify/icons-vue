<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkv48acbf.css';
import '../../css/d/dly27ulfv.css';
import '../../css/x/xa2hfrbrx.css';
import '../../css/w/wbjyenbnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="dkv48acbf"><path class="dly27ulfv"/><path class="wm-k xa2hfrbrx"/><path class="wbjyenbnm wm-a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-kawaii:rangoli-pattern" /></template>
