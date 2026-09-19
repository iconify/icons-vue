<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t37pquajv.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG9IwYberl"><path class="t37pquajv"/></mask></defs><path mask="url(#SVG9IwYberl)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:shield" /></template>
