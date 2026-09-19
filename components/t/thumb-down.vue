<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wqc2c8bli.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wqc2c8bli"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:thumb-down" /></template>
