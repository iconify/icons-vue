<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghhdcccos.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ghhdcccos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:star-half-48" /></template>
