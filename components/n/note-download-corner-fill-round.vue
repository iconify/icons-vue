<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h6nqkob6d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h6nqkob6d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:note-download-corner-fill-round" /></template>
