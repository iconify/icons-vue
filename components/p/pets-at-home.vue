<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vnk1eyalb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vnk1eyalb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:pets-at-home" /></template>
