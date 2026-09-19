<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulz3miwzl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ulz3miwzl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:message-circle" /></template>
