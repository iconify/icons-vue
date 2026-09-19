<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uni_f1bqr.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLikcWbzl"><path class="uni_f1bqr"/></mask></defs><path mask="url(#SVGLikcWbzl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pentagon-one" /></template>
