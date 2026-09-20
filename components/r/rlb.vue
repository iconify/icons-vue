<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/emow59bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="emow59bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rlb" /></template>
