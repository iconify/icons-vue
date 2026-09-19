<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jig3vgbfb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":412,"height":731};
const content = `<path class="jig3vgbfb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:question" /></template>
