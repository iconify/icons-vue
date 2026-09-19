<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es7ggpb0t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":576,"height":512};
const content = `<path class="es7ggpb0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:pills" /></template>
