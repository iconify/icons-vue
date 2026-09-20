<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v847m-bnc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="v847m-bnc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:question-circle" /></template>
