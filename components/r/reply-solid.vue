<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/ddbth32bh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ddbth32bh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:reply-solid" /></template>
