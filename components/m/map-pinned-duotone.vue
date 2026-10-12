<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/o8cx4wb3w.css';
import '../../css/a/ajbec7b6f.css';
import '../../css/n/nl6t94d5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="o8cx4wb3w"/><path clip-rule="evenodd" class="ajbec7b6f"/><path class="nl6t94d5o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:map-pinned-duotone" /></template>
