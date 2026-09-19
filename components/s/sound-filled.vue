<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x2scafb_s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="x2scafb_s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:sound-filled" /></template>
