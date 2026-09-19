<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nkns7hbep.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="nkns7hbep"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:signal" /></template>
