<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p00jiub_r.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlzn6oczD"><path class="p00jiub_r"/></mask></defs><path mask="url(#SVGlzn6oczD)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:windmill-two" /></template>
