<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r6g-cwbpb.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGQlSZBd9z"><path class="r6g-cwbpb"/></mask></defs><path mask="url(#SVGQlSZBd9z)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:trapezoid" /></template>
