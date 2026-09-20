<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wydnq0baj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wydnq0baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pajamas:status-health" /></template>
