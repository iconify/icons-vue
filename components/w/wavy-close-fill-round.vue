<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_l6zjycy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c_l6zjycy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wavy-close-fill-round" /></template>
