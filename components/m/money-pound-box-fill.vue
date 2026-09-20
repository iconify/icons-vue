<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hao75bc9m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hao75bc9m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:money-pound-box-fill" /></template>
