<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/slf5fkzrg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="slf5fkzrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:sonarqube-wordmark" /></template>
