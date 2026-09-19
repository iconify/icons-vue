<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/f/fe9lu6e9u.css';
import '../../css/k/katd21ghy.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGcSnQAbTc"><g class="aql7dnt-u"><path class="fe9lu6e9u"/><path class="katd21ghy"/></g></mask></defs><path mask="url(#SVGcSnQAbTc)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:minus-the-bottom" /></template>
