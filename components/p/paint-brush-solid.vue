<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/im8s7jxin.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="im8s7jxin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons:paint-brush-solid" /></template>
