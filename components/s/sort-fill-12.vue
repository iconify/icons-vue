<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oevo7ab1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="oevo7ab1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="garden:sort-fill-12" /></template>
