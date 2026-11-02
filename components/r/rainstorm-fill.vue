<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ywp966rlz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ywp966rlz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:rainstorm-fill" /></template>
