<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w-pt4ehke.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-pt4ehke"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:shrink" /></template>
