<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chgko6bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chgko6bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:maya-pyramids-fill" /></template>
