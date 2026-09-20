<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ewy0tw_xl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ewy0tw_xl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:x-triangle-solid" /></template>
