<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wue5c4bzg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wue5c4bzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:octagon" /></template>
