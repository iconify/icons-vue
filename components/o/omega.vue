<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wygb0bcec.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wygb0bcec"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:omega" /></template>
