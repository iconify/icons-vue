<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j6hkjtb2k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6hkjtb2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons-bauhaus:music-2" /></template>
