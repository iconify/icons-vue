<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pd7mk0b-g.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pd7mk0b-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:parentheses-ellipsis-solid" /></template>
