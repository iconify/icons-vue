<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l6h7saccw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6h7saccw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:paste-gloss" /></template>
