<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fcs8ekolk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fcs8ekolk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:necktie-solid" /></template>
