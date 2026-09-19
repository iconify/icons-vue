<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ubu5r13hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ubu5r13hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:video-24px" /></template>
