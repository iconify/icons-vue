<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ekgc8_cdh.css';
import '../../css/k/k9y255awr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ekgc8_cdh"/><path class="k9y255awr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:server-48-bold" /></template>
