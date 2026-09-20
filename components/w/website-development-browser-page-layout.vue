<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c7d8-7bnk.css';
import '../../css/l/ljv8sbwcz.css';
import '../../css/t/tf4su8b2i.css';
import '../../css/s/spp8njbrp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7d8-7bnk"/><path class="ljv8sbwcz"/><path class="tf4su8b2i"/><path class="spp8njbrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:website-development-browser-page-layout" /></template>
