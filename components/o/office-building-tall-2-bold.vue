<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hi4pidbeu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hi4pidbeu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:office-building-tall-2-bold" /></template>
