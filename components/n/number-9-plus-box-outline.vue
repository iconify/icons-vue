<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s3ziswbev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s3ziswbev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:number-9-plus-box-outline" /></template>
