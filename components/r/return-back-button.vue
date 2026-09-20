<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efpwwnbho.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="efpwwnbho"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:return-back-button" /></template>
