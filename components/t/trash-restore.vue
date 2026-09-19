<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhu7n8bvi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="bhu7n8bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:trash-restore" /></template>
