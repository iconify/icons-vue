<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/es1ty5o-q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="es1ty5o-q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:medium-m" /></template>
