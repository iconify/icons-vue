<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/ae21gbbfl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ae21gbbfl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteor-icons:wikipedia" /></template>
