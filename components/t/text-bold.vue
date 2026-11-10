<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p40iouuix.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p40iouuix"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:text-bold" /></template>
