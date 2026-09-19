<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/up9n4-7cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="up9n4-7cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:wet-floor" /></template>
