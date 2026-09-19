<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s9cl3zbei.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/q/qkbnnhzhh.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7T0Ivd9S"><g class="s9cl3zbei"><rect class="g47cb4b4t"/><path class="qkbnnhzhh"/></g></mask></defs><path mask="url(#SVG7T0Ivd9S)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:word" /></template>
