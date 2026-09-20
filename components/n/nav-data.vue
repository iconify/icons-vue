<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ejgfz-b4p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ejgfz-b4p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-data" /></template>
