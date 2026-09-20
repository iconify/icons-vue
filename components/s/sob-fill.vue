<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pba4racxx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pba4racxx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:sob-fill" /></template>
