<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u-99x8bls.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="u-99x8bls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:pay-circle-filled" /></template>
