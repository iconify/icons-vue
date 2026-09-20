<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a9l4enb2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a9l4enb2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:stethoscope" /></template>
