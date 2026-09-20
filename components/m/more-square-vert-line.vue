<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f11os4btd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f11os4btd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="si:more-square-vert-line" /></template>
