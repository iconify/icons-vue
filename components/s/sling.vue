<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jnc0q-9gr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path clip-rule="evenodd" class="jnc0q-9gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="healthicons:sling" /></template>
