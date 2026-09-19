<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qnwn4yowi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qnwn4yowi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:unity" /></template>
