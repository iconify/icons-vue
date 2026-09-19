<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uu55eybqf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uu55eybqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:slide" /></template>
