<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e9b7z7bdy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="e9b7z7bdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:mobile-screen-button" /></template>
