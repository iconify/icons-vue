<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwjy8pq2d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwjy8pq2d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:table-columns-split-filled" /></template>
