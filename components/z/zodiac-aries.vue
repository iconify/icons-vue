<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fb8k3dbcn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fb8k3dbcn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vadivam:zodiac-aries" /></template>
