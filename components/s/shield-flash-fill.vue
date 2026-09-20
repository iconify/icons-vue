<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frfs2zneh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="frfs2zneh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:shield-flash-fill" /></template>
