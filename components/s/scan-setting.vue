<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/l/l8-7_vbmo.css';
import '../../css/v/vn2loybei.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSqD1uCIk"><g class="wwvp95byt"><rect class="l8-7_vbmo"/><path class="vn2loybei"/></g></mask></defs><path mask="url(#SVGSqD1uCIk)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:scan-setting" /></template>
