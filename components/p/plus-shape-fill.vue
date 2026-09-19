<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ez-3s-a2s.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ez-3s-a2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:plus-shape-fill" /></template>
