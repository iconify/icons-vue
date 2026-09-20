<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d1ll5c1cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="d1ll5c1cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:python" /></template>
