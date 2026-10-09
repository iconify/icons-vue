<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zq0swu20f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zq0swu20f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:more-vertical-48" /></template>
