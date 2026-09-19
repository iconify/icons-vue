<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vcch-qbaq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vcch-qbaq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:share-20-solid" /></template>
