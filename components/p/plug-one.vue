<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/a/aya53cc9i.css';
import '../../css/o/o93ugkl0y.css';
import '../../css/t/teo97w_bm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9os0Ud9d"><g class="s9cl3zbei"><rect class="aya53cc9i"/><path class="o93ugkl0y"/><path class="teo97w_bm"/></g></mask></defs><path mask="url(#SVG9os0Ud9d)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:plug-one" /></template>
