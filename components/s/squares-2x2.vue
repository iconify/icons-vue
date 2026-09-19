<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fkuzq1bau.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="fkuzq1bau"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:squares-2x2" /></template>
