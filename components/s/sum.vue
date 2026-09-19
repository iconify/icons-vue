<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4xorccrs.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGgtGe9uAZ"><path class="h4xorccrs"/></mask></defs><path mask="url(#SVGgtGe9uAZ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:sum" /></template>
