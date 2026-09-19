<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvl1ieach.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGSTYrZqfb"><path class="cvl1ieach"/></mask></defs><path mask="url(#SVGSTYrZqfb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:octagon" /></template>
