<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r1-rztbxu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r1-rztbxu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:map-gloss" /></template>
