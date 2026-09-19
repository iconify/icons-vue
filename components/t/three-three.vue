<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unmzjbbfs.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGMifv1brb"><path class="unmzjbbfs"/></mask></defs><path mask="url(#SVGMifv1brb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:three-three" /></template>
