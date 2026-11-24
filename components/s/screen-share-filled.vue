<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nod_500mb.css';
import '../../css/q/qb37dcqql.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nod_500mb"/><path class="qb37dcqql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:screen-share-filled" /></template>
