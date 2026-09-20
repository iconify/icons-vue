<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/p3jvn4-di.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p3jvn4-di"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:question-answer" /></template>
