<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uff8yccku.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1664,"height":1664};
const content = `<path class="uff8yccku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:search-minus" /></template>
