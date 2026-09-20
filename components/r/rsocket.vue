<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z9qtyn8ef.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z9qtyn8ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:rsocket" /></template>
