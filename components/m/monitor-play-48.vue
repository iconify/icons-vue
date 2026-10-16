<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/ly_hv7bof.css';
import '../../css/a/azjk1obih.css';
import '../../css/w/w13xa3b8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ly_hv7bof"/><path class="azjk1obih"/><path class="w13xa3b8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:monitor-play-48" /></template>
