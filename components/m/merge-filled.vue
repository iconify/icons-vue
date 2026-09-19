<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz16spphp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="gz16spphp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:merge-filled" /></template>
