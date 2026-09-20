<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mz_6y8b0c.css';
import '../../css/n/nbgejx56b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="mz_6y8b0c"/><path class="nbgejx56b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:mjml" /></template>
