<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tit07-pqz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tit07-pqz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:warm-up-2-fill" /></template>
