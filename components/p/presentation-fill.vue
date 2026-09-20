<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zlr_hjb5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zlr_hjb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:presentation-fill" /></template>
