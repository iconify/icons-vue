<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jvayqlb-e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="jvayqlb-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="selfhst:openai-light" /></template>
