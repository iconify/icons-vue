<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/usl793bzj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="usl793bzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:user-circle" /></template>
