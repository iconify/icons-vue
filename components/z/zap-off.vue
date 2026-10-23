<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b3rs63bdz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3rs63bdz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:zap-off" /></template>
