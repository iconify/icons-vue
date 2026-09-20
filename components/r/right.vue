<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/svujsub8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="svujsub8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uiw:right" /></template>
