<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x7zm9qbfi.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGZZ27B46v"><path class="x7zm9qbfi"/></mask></defs><path mask="url(#SVGZZ27B46v)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:puzzle" /></template>
