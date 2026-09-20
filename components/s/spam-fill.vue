<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y-tu_s2fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-tu_s2fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:spam-fill" /></template>
