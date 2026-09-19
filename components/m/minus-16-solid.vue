<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8h6fkdvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p8h6fkdvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:minus-16-solid" /></template>
