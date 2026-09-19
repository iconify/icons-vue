<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0ly-tbyr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0ly-tbyr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:receipt-outline" /></template>
