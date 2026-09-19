<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/op_bifblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="op_bifblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:search-big-plus-filled" /></template>
