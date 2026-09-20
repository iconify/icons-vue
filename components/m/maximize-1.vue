<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z-3r6qbax.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z-3r6qbax"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-plump:maximize-1" /></template>
