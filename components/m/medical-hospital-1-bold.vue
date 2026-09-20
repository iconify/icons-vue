<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s7hybswkg.css';
import '../../css/o/o08b9ebzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s7hybswkg"/><path class="o08b9ebzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:medical-hospital-1-bold" /></template>
