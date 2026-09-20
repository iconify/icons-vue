<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwg6rltna.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwg6rltna"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi-light:message-image" /></template>
