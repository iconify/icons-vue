<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qknx832so.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGBYCIBewW"><path class="qknx832so"/></mask></defs><path mask="url(#SVGBYCIBewW)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:people" /></template>
