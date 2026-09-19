<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yzqwh5b9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yzqwh5b9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:minus-square-filled" /></template>
