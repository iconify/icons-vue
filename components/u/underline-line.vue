<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_0b-di9n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_0b-di9n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:underline-line" /></template>
