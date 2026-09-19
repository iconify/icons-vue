<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e3lm1rjzu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="e3lm1rjzu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:microsoft-infopath" /></template>
