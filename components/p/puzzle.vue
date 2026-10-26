<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rk524nb7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rk524nb7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:puzzle" /></template>
