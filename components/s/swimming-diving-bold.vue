<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qn-qwxbxy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qn-qwxbxy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:swimming-diving-bold" /></template>
