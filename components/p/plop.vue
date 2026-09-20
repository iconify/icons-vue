<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gdz8q2beh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":250,"height":250};
const content = `<path clip-rule="evenodd" class="gdz8q2beh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:plop" /></template>
