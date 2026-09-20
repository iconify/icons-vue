<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xd2m22lpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xd2m22lpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="prime:th-large" /></template>
