<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ir0fna9cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir0fna9cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:paragliding" /></template>
