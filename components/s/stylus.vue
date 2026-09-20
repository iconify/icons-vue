<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jpgbqyjja.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jpgbqyjja"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:stylus" /></template>
