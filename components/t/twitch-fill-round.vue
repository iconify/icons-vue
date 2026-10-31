<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pxxamib7d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pxxamib7d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:twitch-fill-round" /></template>
