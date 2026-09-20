<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tkrjhob6y.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tkrjhob6y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="oui:nav-reports" /></template>
