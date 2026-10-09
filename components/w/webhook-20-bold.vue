<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/ki204cc1a.css';
import '../../css/x/xe7g4rbrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ki204cc1a"/><path class="xe7g4rbrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:webhook-20-bold" /></template>
