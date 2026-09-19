<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kt7s3r6xk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="kt7s3r6xk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:tool" /></template>
