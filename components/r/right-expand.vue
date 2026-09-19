<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aql7dnt-u.css';
import '../../css/k/kieu5bcnf.css';
import '../../css/n/ngen0gb1d.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVG5u2Fgb3A"><g class="aql7dnt-u"><rect class="kieu5bcnf"/><path class="ngen0gb1d"/></g></mask></defs><path mask="url(#SVG5u2Fgb3A)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:right-expand" /></template>
