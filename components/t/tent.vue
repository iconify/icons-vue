<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wwvp95byt.css';
import '../../css/q/q_2m_xbrx.css';
import '../../css/z/z1jwvkgas.css';
import '../../css/y/y3z90mb8g.css';
import '../../css/r/r6femfb0m.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGScXhYdjV"><g class="wwvp95byt"><path class="q_2m_xbrx"/><path class="z1jwvkgas"/><path class="y3z90mb8g"/><path class="r6femfb0m"/></g></mask></defs><path mask="url(#SVGScXhYdjV)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:tent" /></template>
