<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gii8w5ebd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gii8w5ebd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-devtools" /></template>
