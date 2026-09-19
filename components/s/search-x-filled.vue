<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rx7g8xu8c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rx7g8xu8c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-x-filled" /></template>
