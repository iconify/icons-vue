<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ie6ox79cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":350,"height":512};
const content = `<path class="ie6ox79cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="file-icons:scheme" /></template>
