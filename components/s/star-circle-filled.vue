<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb0yj6ylj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb0yj6ylj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:star-circle-filled" /></template>
