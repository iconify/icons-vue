<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2stgebyp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG4yRl9bjc"><circle class="z2stgebyp"/></mask></defs><path mask="url(#SVG4yRl9bjc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:round" /></template>
