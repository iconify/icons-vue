<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/u4b7xfb9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u4b7xfb9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:safety-certificate-line" /></template>
