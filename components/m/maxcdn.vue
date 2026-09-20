<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ear6xob-i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ear6xob-i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:maxcdn" /></template>
