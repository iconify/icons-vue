<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mtm_fmbjl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="mtm_fmbjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:wallet-filled" /></template>
