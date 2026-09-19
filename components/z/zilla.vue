<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wdit_gbux.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wdit_gbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cryptocurrency:zilla" /></template>
