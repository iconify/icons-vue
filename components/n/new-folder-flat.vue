<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bgb52ccwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bgb52ccwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp-color:new-folder-flat" /></template>
