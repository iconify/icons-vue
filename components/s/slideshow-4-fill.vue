<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p8-sadbvl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p8-sadbvl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:slideshow-4-fill" /></template>
