<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xn7foybwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xn7foybwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-right-fill" /></template>
