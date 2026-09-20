<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h96hfv_iy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="h96hfv_iy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="radix-icons:minus-circled" /></template>
