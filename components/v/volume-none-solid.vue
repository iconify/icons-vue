<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t9xpa4bxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9xpa4bxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:volume-none-solid" /></template>
