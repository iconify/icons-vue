<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0tpdz_cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="d0tpdz_cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="qlementine-icons:resize-horizontal-16" /></template>
