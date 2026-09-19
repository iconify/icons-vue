<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zg69u6buu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zg69u6buu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:receipt-alt-filled" /></template>
