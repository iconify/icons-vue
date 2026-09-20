<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fokxw6bem.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fokxw6bem"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:telephone-call" /></template>
