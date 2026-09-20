<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tt-78lqjh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tt-78lqjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-voice" /></template>
