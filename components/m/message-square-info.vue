<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i02gv5wud.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="i02gv5wud"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:message-square-info" /></template>
