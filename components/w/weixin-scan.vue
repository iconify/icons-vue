<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ldqlsxbum.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGv2537bBg"><path class="ldqlsxbum"/></mask></defs><path mask="url(#SVGv2537bBg)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:weixin-scan" /></template>
