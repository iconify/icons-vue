<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/unqzfdcpy.css';
import '../../css/p/pqf5v6bke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="unqzfdcpy"/><path class="pqf5v6bke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:sort-asc-48" /></template>
