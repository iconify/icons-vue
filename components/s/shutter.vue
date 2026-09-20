<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xja5e1bfy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xja5e1bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:shutter" /></template>
