<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg8ef5bno.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg8ef5bno"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:text-align-center-solid" /></template>
