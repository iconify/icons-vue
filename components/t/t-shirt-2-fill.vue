<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/has-te2vt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="has-te2vt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:t-shirt-2-fill" /></template>
