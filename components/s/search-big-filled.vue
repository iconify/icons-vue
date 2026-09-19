<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zbv6qjqqs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zbv6qjqqs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-big-filled" /></template>
