<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ec-8ohbed.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGRWh4Mdhm"><path class="ec-8ohbed"/></mask></defs><path mask="url(#SVGRWh4Mdhm)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:triangle-round-rectangle" /></template>
