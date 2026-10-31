<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ixtq4fzpl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ixtq4fzpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:panel-bottom-gloss" /></template>
