<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cymmyqb3s.css';
import '../../css/f/f0d5hoc7t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":72,"height":72};
const content = `<path class="cymmyqb3s"/><path class="f0d5hoc7t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="openmoji:play-button" /></template>
