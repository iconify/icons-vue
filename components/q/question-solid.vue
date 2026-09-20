<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uyqfjogqv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uyqfjogqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pixel:question-solid" /></template>
