<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/luuhupbtk.css';
import '../../css/g/gtinig8dd.css';
import '../../css/u/umj1g9evr.css';
import '../../css/d/d3u3pvbaj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="luuhupbtk"/><path class="gtinig8dd"/><path class="umj1g9evr"/><path class="d3u3pvbaj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:monitor" /></template>
