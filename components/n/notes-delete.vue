<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l7iq23b_v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l7iq23b_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixelarticons:notes-delete" /></template>
