<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uztu22bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uztu22bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:octocat-fill" /></template>
