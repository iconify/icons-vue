<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fs6_p0ttt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fs6_p0ttt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:upload-fill" /></template>
