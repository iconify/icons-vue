<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mb-7hwcld.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mb-7hwcld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide:table-rows-split" /></template>
