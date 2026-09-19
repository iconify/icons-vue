<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvjowitwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="tvjowitwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:open-book-small" /></template>
