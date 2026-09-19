<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/v/ven960eol.css';
import '../../css/f/fmc-dpppl.css';
import '../../css/o/ocv1-uqro.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCrHiRbFp"><g class="wwvp95byt"><path class="ven960eol"/><path class="fmc-dpppl"/><path class="ocv1-uqro"/></g></mask></defs><path mask="url(#SVGCrHiRbFp)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:tips" /></template>
