<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/aodokebob.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aodokebob"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:trush-square-filled" /></template>
