<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpeowxwxq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpeowxwxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:reply-linear" /></template>
