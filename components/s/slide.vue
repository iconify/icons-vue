<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/npwtvccwm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="npwtvccwm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:slide" /></template>
