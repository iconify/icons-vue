<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yqv09lbxb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yqv09lbxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:user-minus-filled" /></template>
