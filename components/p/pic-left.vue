<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ft6y81b-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ft6y81b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pic-left" /></template>
