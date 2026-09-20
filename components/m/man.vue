<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kefy6rber.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="kefy6rber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="raphael:man" /></template>
