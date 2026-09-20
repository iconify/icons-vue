<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n3glxibdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n3glxibdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:margin-right" /></template>
