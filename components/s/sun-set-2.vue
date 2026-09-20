<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxjk6z-uv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zxjk6z-uv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-cyber:sun-set-2" /></template>
