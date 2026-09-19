<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/p/pi9a0sbaf.css';
import '../../css/t/tvgk8qbnj.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGjOJgrbjt"><g class="ft5dv1b6b"><path class="pi9a0sbaf"/><path class="tvgk8qbnj"/></g></mask></defs><path mask="url(#SVGjOJgrbjt)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:server" /></template>
