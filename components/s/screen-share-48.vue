<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly_hv7bof.css';
import '../../css/a/azjk1obih.css';
import '../../css/h/hdktsfu6p.css';
import '../../css/u/u5zilgbbx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ly_hv7bof"/><path class="azjk1obih"/><path class="hdktsfu6p"/><path class="u5zilgbbx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:screen-share-48" /></template>
