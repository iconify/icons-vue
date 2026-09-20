<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yno2t3b3s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yno2t3b3s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:minetest" /></template>
