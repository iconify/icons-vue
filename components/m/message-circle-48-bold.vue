<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ahnwm4b0f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ahnwm4b0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:message-circle-48-bold" /></template>
