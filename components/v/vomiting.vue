<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js6bkmb4f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="js6bkmb4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:vomiting" /></template>
