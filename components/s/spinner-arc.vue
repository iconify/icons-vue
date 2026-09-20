<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nil9-lhla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nil9-lhla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:spinner-arc" /></template>
