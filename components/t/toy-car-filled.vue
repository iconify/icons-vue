<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q3j3b2bnm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q3j3b2bnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:toy-car-filled" /></template>
