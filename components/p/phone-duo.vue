<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/exv0g4bou.css';
import '../../css/y/ymkt-qbpr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exv0g4bou secondary"/><path class="primary ymkt-qbpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:phone-duo" /></template>
