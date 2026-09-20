<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/np6b41bky.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="np6b41bky"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:xmark" /></template>
