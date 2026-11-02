<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i5504zl5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i5504zl5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:toggle-left-2-line" /></template>
