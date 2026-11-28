<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/b2z9d7bwa.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2z9d7bwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconaut:save-solid" /></template>
