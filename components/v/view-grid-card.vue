<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g47cb4b4t.css';
import '../../css/y/y--o70bgp.css';
import '../../css/b/bl95smbeo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGn6qAgcgy"><g class="ufeehvblu"><rect class="g47cb4b4t"/><path class="y--o70bgp"/></g></mask></defs><path mask="url(#SVGn6qAgcgy)" class="bl95smbeo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-solid:view-grid-card" /></template>
