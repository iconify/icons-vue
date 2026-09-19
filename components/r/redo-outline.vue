<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pyp3-vbdx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyp3-vbdx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="flowbite:redo-outline" /></template>
