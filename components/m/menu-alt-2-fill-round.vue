<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f5jngf2xf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f5jngf2xf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:menu-alt-2-fill-round" /></template>
