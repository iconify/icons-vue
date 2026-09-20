<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q9zetgbfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q9zetgbfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:welcome-to-the-jungle" /></template>
