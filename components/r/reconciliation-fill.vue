<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m9uk8bgdh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="m9uk8bgdh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:reconciliation-fill" /></template>
