<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nne_osbxz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nne_osbxz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:save-outlined" /></template>
