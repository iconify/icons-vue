<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ehiw4ce2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ehiw4ce2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:share" /></template>
