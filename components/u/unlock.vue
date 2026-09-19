<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/w/wjmi2eb4l.css';
import '../../css/e/ej3cr6b9e.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGbQ8yscDi"><g class="v3_i3wktz"><rect class="wjmi2eb4l"/><path class="ej3cr6b9e"/></g></mask></defs><path mask="url(#SVGbQ8yscDi)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:unlock" /></template>
