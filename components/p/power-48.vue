<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pect2h6nx.css';
import '../../css/e/ejop8g90f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pect2h6nx"/><path class="ejop8g90f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:power-48" /></template>
