<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xvfujmbgg.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGFlF8Ac6N"><path class="xvfujmbgg"/></mask></defs><path mask="url(#SVGFlF8Ac6N)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:rectangle-small" /></template>
