<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qln0q4btt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qln0q4btt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:message-down" /></template>
