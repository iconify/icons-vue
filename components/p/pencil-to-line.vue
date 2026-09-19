<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/izny3lyjm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="izny3lyjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="gravity-ui:pencil-to-line" /></template>
