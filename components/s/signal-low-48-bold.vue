<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n9sm63b6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n9sm63b6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:signal-low-48-bold" /></template>
