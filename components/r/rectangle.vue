<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f9ga5g8gl.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG7t90jevq"><path class="f9ga5g8gl"/></mask></defs><path mask="url(#SVG7t90jevq)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:rectangle" /></template>
