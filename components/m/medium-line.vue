<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a_nde8b2s.css';
import '../../css/f/f0yq_obue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a_nde8b2s"/><path class="f0yq_obue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:medium-line" /></template>
