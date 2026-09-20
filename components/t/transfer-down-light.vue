<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/onhuknpmz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="onhuknpmz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lets-icons:transfer-down-light" /></template>
