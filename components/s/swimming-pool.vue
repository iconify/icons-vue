<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ml4dr2hga.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ml4dr2hga"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icon-park-outline:swimming-pool" /></template>
