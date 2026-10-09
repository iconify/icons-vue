<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tbfu520ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tbfu520ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:swimming-48" /></template>
