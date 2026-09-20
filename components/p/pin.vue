<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yya7h_b_g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yya7h_b_g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:pin" /></template>
