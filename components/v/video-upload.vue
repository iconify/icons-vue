<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ipq1z-bjh.css';
import '../../css/s/szgxpndjz.css';
import '../../css/y/yl-w2ab9g.css';
import '../../css/v/voojxubbp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="szgxpndjz"/><path class="yl-w2ab9g"/><path class="voojxubbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:video-upload" /></template>
