<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hxj2tvb8n.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hxj2tvb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="stash:sliders-v-light" /></template>
