<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yu8lg6sbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yu8lg6sbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:message-circle-more-gloss" /></template>
