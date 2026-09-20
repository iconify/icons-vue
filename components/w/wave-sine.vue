<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnqe827se.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnqe827se"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:wave-sine" /></template>
