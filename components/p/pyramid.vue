<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/soze-xbbu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="soze-xbbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:pyramid" /></template>
