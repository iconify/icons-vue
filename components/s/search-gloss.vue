<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pnu8yeb7q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnu8yeb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:search-gloss" /></template>
