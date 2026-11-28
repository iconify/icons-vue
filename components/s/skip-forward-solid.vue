<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqf4fxbwb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pqf4fxbwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:skip-forward-solid" /></template>
