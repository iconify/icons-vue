<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbfnm8qwj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbfnm8qwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:twinkly-squares" /></template>
