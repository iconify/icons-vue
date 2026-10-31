<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ik89tg8wn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ik89tg8wn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:zoom-in-gloss" /></template>
