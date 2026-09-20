<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lqyvc6bng.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lqyvc6bng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mynaui:snow" /></template>
