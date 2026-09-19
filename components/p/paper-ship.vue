<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v3_i3wktz.css';
import '../../css/q/q9z220ulp.css';
import '../../css/b/b98o3ib5q.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGlcr4TdQJ"><g class="v3_i3wktz"><path class="q9z220ulp"/><path class="b98o3ib5q"/></g></mask></defs><path mask="url(#SVGlcr4TdQJ)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-twotone:paper-ship" /></template>
