<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yx-md1bnr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx-md1bnr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:save-gloss" /></template>
