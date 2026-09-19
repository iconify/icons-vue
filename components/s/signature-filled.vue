<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y35j6lhfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="y35j6lhfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:signature-filled" /></template>
