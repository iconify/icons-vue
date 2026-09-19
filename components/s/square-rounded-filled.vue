<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sc10kobev.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sc10kobev"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:square-rounded-filled" /></template>
