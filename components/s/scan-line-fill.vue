<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kb4ehwboh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kb4ehwboh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:scan-line-fill" /></template>
