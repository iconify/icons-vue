<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zeofr7ors.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zeofr7ors"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:table-search" /></template>
