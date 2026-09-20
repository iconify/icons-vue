<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jdv1hacji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jdv1hacji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:odoo" /></template>
