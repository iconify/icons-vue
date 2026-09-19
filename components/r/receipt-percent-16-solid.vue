<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/leera0b-z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="leera0b-z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:receipt-percent-16-solid" /></template>
