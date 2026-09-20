<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zk2lukbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zk2lukbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lineicons:oculus" /></template>
