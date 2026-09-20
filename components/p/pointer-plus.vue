<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ud8nhc1pq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ud8nhc1pq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:pointer-plus" /></template>
