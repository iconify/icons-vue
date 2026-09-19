<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oz6-5w-0c.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="oz6-5w-0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:setting-outline" /></template>
