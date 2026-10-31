<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/ghomjxdge.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ghomjxdge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:radio-receiver-duocolor-round" /></template>
