<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axcd-nboi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="axcd-nboi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:smr-48" /></template>
