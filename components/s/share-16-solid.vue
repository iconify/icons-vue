<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc99t7udr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qc99t7udr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:share-16-solid" /></template>
