<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jy062-bze.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jy062-bze"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:r" /></template>
