<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jkbledcac.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jkbledcac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:sticky-note-solid" /></template>
