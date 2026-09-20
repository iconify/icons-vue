<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fab0zybii.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fab0zybii"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:roadmapdotsh" /></template>
