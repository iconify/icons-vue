<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8jsn2i4o.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGEpqjdbuG"><path class="e8jsn2i4o"/></mask></defs><path mask="url(#SVGEpqjdbuG)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pin" /></template>
