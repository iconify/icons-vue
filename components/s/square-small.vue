<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/ppbk3zbaq.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGve42mdIb"><path class="ppbk3zbaq"/></mask></defs><path mask="url(#SVGve42mdIb)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:square-small" /></template>
