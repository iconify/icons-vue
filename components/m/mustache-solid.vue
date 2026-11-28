<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/cm54o-gwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cm54o-gwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:mustache-solid" /></template>
