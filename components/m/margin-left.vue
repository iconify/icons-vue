<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5f3mdlnx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t5f3mdlnx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:margin-left" /></template>
