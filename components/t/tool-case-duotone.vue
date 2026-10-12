<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/a/aoz-vgokd.css';
import '../../css/s/s3asngb_b.css';
import '../../css/n/n171dubne.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="aoz-vgokd"/><path class="s3asngb_b"/><path class="n171dubne"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:tool-case-duotone" /></template>
