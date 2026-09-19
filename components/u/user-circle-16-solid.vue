<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g7r4tcwgg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="g7r4tcwgg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:user-circle-16-solid" /></template>
