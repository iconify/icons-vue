<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwqdbnx5o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="hwqdbnx5o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:minus-circle-20-solid" /></template>
