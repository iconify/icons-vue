<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gkje3ybpz.css';
import '../../css/u/udqbpfbup.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gkje3ybpz"/><path class="udqbpfbup"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:search-sparkle-48" /></template>
