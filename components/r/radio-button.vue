<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/axq-915ji.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="axq-915ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:radio-button" /></template>
