<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v0lidos6q.css';
import '../../css/f/fokf_m9cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="v0lidos6q"/><path class="fokf_m9cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vaadin:tools" /></template>
