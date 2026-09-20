<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fn2qr4boh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fn2qr4boh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:tune-adjust-volume-remix" /></template>
