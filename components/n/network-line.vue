<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f3b9acb4r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f3b9acb4r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:network-line" /></template>
