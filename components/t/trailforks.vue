<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i9tanvb1z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i9tanvb1z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:trailforks" /></template>
