<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h01tyzbfu.css';
import '../../css/x/x-1sijr5f.css';
import '../../css/d/dt-gdj9go.css';
import '../../css/u/urjx-ibsa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="h01tyzbfu"><path class="x-1sijr5f"/><path class="dt-gdj9go"/><path class="urjx-ibsa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="bitcoin-icons:tag-outline" /></template>
