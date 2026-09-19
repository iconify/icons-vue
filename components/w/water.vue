<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e4wngcb6p.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGhOoFSdeL"><path class="e4wngcb6p"/></mask></defs><path mask="url(#SVGhOoFSdeL)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:water" /></template>
