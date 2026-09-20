<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iipx-2axi.css';
import '../../css/w/wb8zavuhy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="iipx-2axi"/><path clip-rule="evenodd" class="wb8zavuhy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:ui-panel-bottom-16" /></template>
