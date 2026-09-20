<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/em1zy3qkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="em1zy3qkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:space-invaders" /></template>
