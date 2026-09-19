<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gnj62obrz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="gnj62obrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:photo-20-solid" /></template>
