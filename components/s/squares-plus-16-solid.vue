<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v19ilacll.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v19ilacll"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:squares-plus-16-solid" /></template>
