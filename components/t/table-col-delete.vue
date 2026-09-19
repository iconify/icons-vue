<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tqp9l5bag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tqp9l5bag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dashicons:table-col-delete" /></template>
