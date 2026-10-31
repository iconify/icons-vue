<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h4bdb01hm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h4bdb01hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:washing-machine-gloss" /></template>
