<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z0kl24bxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z0kl24bxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:rewind-start-mini-fill" /></template>
