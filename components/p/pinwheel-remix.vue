<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgaj7hb_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="qgaj7hb_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:pinwheel-remix" /></template>
