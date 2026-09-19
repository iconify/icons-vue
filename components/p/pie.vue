<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/k/kb9zbkb1z.css';
import '../../css/y/ybatxgbvz.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGLbKKgdNp"><g class="aql7dnt-u"><circle class="kb9zbkb1z"/><path class="ybatxgbvz"/></g></mask></defs><path mask="url(#SVGLbKKgdNp)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:pie" /></template>
