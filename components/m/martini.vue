<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tylz4_gen.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tylz4_gen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:martini" /></template>
