<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ak2bjr-cn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ak2bjr-cn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tdesign:numbers-5-1" /></template>
