<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tr4wmqb0l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="tr4wmqb0l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="doodle-icons:text-align-end" /></template>
