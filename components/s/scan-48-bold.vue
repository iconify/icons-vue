<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ihdvcd13a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ihdvcd13a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:scan-48-bold" /></template>
