<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axjgsy3nl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="axjgsy3nl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg-color:riot-games" /></template>
