<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/i/i9dcd_-yi.css';
import '../../css/k/k132ggb9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":400,"height":400};
const content = `<g class="ft5dv1b6b"><rect class="i9dcd_-yi"/><path clip-rule="evenodd" class="k132ggb9i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:midday" /></template>
