<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s6omv9b3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="s6omv9b3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:toolbox-gloss" /></template>
