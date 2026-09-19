<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hvko1jboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":23,"height":24};
const content = `<path class="hvko1jboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fontisto:nav-icon-grid-a" /></template>
