<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_qksxbla.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h_qksxbla"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:pencil-20-solid" /></template>
