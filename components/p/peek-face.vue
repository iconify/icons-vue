<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/h8l4m88zg.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="h8l4m88zg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:peek-face" /></template>
