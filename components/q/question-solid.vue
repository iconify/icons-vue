<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/efp6idufy.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="efp6idufy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:question-solid" /></template>
