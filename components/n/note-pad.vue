<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/frsy2rb9z.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":80,"height":80};
const content = `<path class="frsy2rb9z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="glyphs:note-pad" /></template>
