<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i1u8bfmde.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":22,"height":22};
const content = `<path class="i1u8bfmde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="memory:message-user" /></template>
