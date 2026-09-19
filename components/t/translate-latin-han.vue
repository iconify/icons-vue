<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z59vvfb-x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="z59vvfb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="dinkie-icons:translate-latin-han" /></template>
