<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kh8byk_qa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kh8byk_qa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:map-marker" /></template>
