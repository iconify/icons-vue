<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/m/mzszod_2j.css';
import '../../css/h/hiquibbwj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGdAUN9bOF"><g class="s9cl3zbei"><circle class="mzszod_2j"/><circle class="hiquibbwj"/></g></mask></defs><path mask="url(#SVGdAUN9bOF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:radio-two" /></template>
