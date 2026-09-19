<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y6acdcbet.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y6acdcbet"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:menu" /></template>
