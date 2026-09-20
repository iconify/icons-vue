<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gz5b7sfon.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gz5b7sfon"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:user-check-sharp" /></template>
