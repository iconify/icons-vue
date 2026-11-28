<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fsy0fcbgt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsy0fcbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:merge" /></template>
