<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zmbg79_il.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zmbg79_il"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:wifi-minus-solid" /></template>
