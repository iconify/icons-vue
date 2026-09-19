<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vbdb5tbal.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbdb5tbal"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="hugeicons:right-to-left-list-triangle" /></template>
