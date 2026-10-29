<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gesw5mb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gesw5mb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:panels-right-bottom" /></template>
