<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nu6ys3bzz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nu6ys3bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:surf-48-bold" /></template>
