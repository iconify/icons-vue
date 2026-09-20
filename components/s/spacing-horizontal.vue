<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ilma44bvo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ilma44bvo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="tabler:spacing-horizontal" /></template>
