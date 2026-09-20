<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lewpyxb3u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lewpyxb3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:zoom-out-line" /></template>
