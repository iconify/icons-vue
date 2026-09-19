<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/o/oc1spnb4j.css';
import '../../css/y/y1_alg6mo.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGxGKFOeVC"><g class="aql7dnt-u"><rect class="oc1spnb4j"/><path class="y1_alg6mo"/></g></mask></defs><path mask="url(#SVGxGKFOeVC)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:trunk" /></template>
