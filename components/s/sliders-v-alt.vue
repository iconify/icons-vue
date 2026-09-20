<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mmmqw062e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mmmqw062e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uil:sliders-v-alt" /></template>
