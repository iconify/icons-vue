<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/o/o57zbkbrr.css';
import '../../css/v/vtzd9e8ey.css';
import '../../css/h/hqxzmxbzb.css';
import '../../css/c/c4vh84bvt.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGpWqCzeUR"><g class="s9cl3zbei"><path class="o57zbkbrr"/><path class="vtzd9e8ey"/><path class="hqxzmxbzb"/><path class="c4vh84bvt"/></g></mask></defs><path mask="url(#SVGpWqCzeUR)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:plan" /></template>
