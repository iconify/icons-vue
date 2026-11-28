<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/td3kli-dq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="td3kli-dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:shovel-solid" /></template>
