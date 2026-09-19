<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h9pel1xle.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h9pel1xle"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:scart" /></template>
