<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dayaw-b9i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":77,"height":614};
const content = `<path class="dayaw-b9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:periodcentered" /></template>
