<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/ya-e6tb3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ya-e6tb3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token:rlc" /></template>
