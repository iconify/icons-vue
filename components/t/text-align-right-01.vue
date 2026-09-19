<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wpjdfxbzr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wpjdfxbzr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:text-align-right-01" /></template>
