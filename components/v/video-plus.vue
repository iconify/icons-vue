<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fqz833imf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="fqz833imf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:video-plus" /></template>
