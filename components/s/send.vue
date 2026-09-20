<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xacg5pbsc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xacg5pbsc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:send" /></template>
