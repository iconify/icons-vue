<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twyyp55es.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="twyyp55es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:outdoor-motion" /></template>
