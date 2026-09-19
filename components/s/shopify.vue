<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma39zmb0k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":452,"height":512};
const content = `<path class="ma39zmb0k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:shopify" /></template>
