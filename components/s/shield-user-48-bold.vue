<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ce0cywmuu.css';
import '../../css/c/cmhn4ab9f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ce0cywmuu"/><path class="cmhn4ab9f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shield-user-48-bold" /></template>
