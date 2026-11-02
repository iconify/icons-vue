<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj3r7hxgo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zj3r7hxgo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scooter-fill" /></template>
