<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-ndh8igt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o-ndh8igt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-big-x-filled" /></template>
