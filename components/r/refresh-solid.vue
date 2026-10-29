<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/enqf0ab1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="enqf0ab1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:refresh-solid" /></template>
