<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvy5cdb3y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dvy5cdb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:plane-gloss" /></template>
