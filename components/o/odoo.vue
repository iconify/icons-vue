<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rb9c2sbsb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rb9c2sbsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:odoo" /></template>
