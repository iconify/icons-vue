<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o8wq1obhk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="o8wq1obhk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:thumbs-up" /></template>
