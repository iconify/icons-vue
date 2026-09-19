<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e8anjebdg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="e8anjebdg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:pencil-small" /></template>
