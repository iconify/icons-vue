<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/j_264jbws.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j_264jbws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:toy-brick-marker-outline" /></template>
