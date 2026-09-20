<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cdtkkuksl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cdtkkuksl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:plus-lock-open" /></template>
