<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c0dz9vbag.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c0dz9vbag"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:pause-gloss" /></template>
