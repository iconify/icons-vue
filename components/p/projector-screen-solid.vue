<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/had-semte.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="had-semte"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:projector-screen-solid" /></template>
