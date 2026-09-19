<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi0-grw5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":460,"height":512};
const content = `<path class="hi0-grw5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:openpolicyagent" /></template>
