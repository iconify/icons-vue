<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wlnvach5k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wlnvach5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-download-fill-round" /></template>
