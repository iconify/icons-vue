<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g9aa3wsrh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g9aa3wsrh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:synagogue-round" /></template>
