<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6g4xkuqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i6g4xkuqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair:tulip-heart" /></template>
