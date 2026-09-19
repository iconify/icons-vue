<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bcxs87bij.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="bcxs87bij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:trademark-circle-filled" /></template>
