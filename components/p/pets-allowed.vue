<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jyqp8gbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jyqp8gbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="guidance:pets-allowed" /></template>
