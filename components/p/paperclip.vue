<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h_bokxx-w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h_bokxx-w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:paperclip" /></template>
