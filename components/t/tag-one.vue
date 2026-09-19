<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/w35a9ksvv.css';
import '../../css/s/s0wvueb0a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="ft5dv1b6b"><path class="w35a9ksvv"/><path clip-rule="evenodd" class="s0wvueb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park:tag-one" /></template>
