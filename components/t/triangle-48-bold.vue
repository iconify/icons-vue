<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bnut6ab4j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="bnut6ab4j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:triangle-48-bold" /></template>
