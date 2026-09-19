<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i186x-vtx.css';
import '../../css/i/ivau6ccrv.css';
import '../../css/v/vjtndybvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i186x-vtx"/><path class="ivau6ccrv"/><path class="vjtndybvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flat-color-icons:vlc" /></template>
