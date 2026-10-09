<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n6sb2hngk.css';
import '../../css/n/nnm25rbzu.css';
import '../../css/d/drgos1k9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="n6sb2hngk"/><path class="nnm25rbzu"/><path class="drgos1k9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:webcam-20" /></template>
