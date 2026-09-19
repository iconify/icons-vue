<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/epnoz8anu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epnoz8anu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="humbleicons:pill-off" /></template>
