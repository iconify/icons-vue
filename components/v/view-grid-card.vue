<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ylrso7y3c.css';
import '../../css/r/r8cyu3bwz.css';
import '../../css/t/thew5jb6s.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGCxcX3bgT"><g class="ylrso7y3c"><rect class="r8cyu3bwz"/><path class="thew5jb6s"/></g></mask></defs><path mask="url(#SVGCxcX3bgT)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:view-grid-card" /></template>
