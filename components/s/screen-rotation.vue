<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/f2e3a6bxc.css';
import '../../css/v/vis7orbfm.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG8G5P1bdF"><g class="aql7dnt-u"><path class="f2e3a6bxc"/><path class="vis7orbfm"/></g></mask></defs><path mask="url(#SVG8G5P1bdF)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:screen-rotation" /></template>
