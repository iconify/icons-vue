<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hjgo7vbra.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hjgo7vbra"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:pen" /></template>
