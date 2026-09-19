<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b77c3o1cy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b77c3o1cy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-outline:minus" /></template>
