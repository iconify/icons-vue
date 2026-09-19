<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/f/fux8zqblx.css';
import '../../css/l/l5mclvbum.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGGwFpddgU"><g class="ft5dv1b6b"><path class="fux8zqblx"/><path class="l5mclvbum"/></g></mask></defs><path mask="url(#SVGGwFpddgU)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:tumblr" /></template>
