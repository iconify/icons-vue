<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jgy8--9nd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jgy8--9nd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:panoramic-screen-solid" /></template>
