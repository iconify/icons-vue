<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r9y7s-r2s.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGJzsKOqQJ"><path class="r9y7s-r2s"/></mask></defs><path mask="url(#SVGJzsKOqQJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:point-out" /></template>
