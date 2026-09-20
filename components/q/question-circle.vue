<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l9g73hbai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l9g73hbai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:question-circle" /></template>
