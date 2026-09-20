<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/blxa5_b8f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="blxa5_b8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:message-processing" /></template>
