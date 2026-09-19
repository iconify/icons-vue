<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/ftf0vwb1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ftf0vwb1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:nhibernate-wordmark" /></template>
