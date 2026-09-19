<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/z/zfyl27hec.css';
import '../../css/v/v4b5s9tmh.css';
import '../../css/g/gv3y-d4kx.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG92zufcFq"><g class="ft5dv1b6b"><rect class="zfyl27hec"/><path class="v4b5s9tmh"/><path class="gv3y-d4kx"/></g></mask></defs><path mask="url(#SVG92zufcFq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:medicine-chest" /></template>
