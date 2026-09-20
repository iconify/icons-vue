<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_6gxfbqx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="f_6gxfbqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:t-shirt-outline" /></template>
