<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hyqx-3brr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hyqx-3brr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:music" /></template>
