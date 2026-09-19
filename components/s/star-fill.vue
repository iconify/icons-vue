<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/llgy7otxe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="llgy7otxe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eva:star-fill" /></template>
