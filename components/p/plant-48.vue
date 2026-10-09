<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cpqtu-bsh.css';
import '../../css/c/cq09toq9d.css';
import '../../css/l/lmmaxg6dh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cpqtu-bsh"/><path class="cq09toq9d"/><path class="lmmaxg6dh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:plant-48" /></template>
