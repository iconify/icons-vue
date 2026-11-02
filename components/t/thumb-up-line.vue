<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-qpp8bff.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-qpp8bff"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:thumb-up-line" /></template>
