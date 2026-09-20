<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nnorrgb5d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nnorrgb5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:volume-sleep" /></template>
