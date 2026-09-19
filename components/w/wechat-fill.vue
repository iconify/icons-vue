<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxw6q2beu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nxw6q2beu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:wechat-fill" /></template>
