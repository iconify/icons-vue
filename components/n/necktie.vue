<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hbbfu8bow.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hbbfu8bow"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:necktie" /></template>
