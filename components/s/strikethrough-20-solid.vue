<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g341omwco.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="g341omwco"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:strikethrough-20-solid" /></template>
