<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/quzl6dbdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="quzl6dbdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="boxicons:set-intersection-filled" /></template>
