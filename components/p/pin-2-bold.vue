<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iz4gg-7av.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iz4gg-7av"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:pin-2-bold" /></template>
