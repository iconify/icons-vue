<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyja_c0px.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyja_c0px"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:rabbit-gloss" /></template>
