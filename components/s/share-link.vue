<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bhbc-tbqr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bhbc-tbqr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-sharp:share-link" /></template>
