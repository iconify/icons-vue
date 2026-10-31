<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kbgj9ebag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kbgj9ebag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:microscope-gloss" /></template>
