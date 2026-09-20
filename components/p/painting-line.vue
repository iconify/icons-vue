<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dkr9t4bzp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dkr9t4bzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:painting-line" /></template>
