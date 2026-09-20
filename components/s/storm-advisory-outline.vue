<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lzow25bmr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lzow25bmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:storm-advisory-outline" /></template>
