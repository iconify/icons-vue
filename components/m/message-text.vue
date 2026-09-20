<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie0e-hgta.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ie0e-hgta"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:message-text" /></template>
