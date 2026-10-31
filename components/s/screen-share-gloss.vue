<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hfjxybb7f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hfjxybb7f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:screen-share-gloss" /></template>
