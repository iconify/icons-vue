<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cvho9y7-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cvho9y7-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:megaphone-line" /></template>
