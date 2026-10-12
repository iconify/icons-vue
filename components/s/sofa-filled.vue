<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fffgk-bgb.css';
import '../../css/s/s88v5t7cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fffgk-bgb"/><path class="s88v5t7cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:sofa-filled" /></template>
