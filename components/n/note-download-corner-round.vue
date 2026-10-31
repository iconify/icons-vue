<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/esa6zfg6u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="esa6zfg6u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-download-corner-round" /></template>
