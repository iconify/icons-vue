<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zwdbip3wj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zwdbip3wj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:thumbs-down-gloss" /></template>
