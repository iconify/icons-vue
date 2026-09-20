<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gp_8x1bzb.css';
import '../../css/y/ymwuqkrmm.css';
import '../../css/m/mdnzfy8ny.css';
import '../../css/e/e9_804b6c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="ymwuqkrmm"/><path class="mdnzfy8ny"/><path class="e9_804b6c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pen-off-sharp-two-tone" /></template>
