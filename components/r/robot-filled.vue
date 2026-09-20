<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e54p_3stm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e54p_3stm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:robot-filled" /></template>
