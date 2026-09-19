<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fu4lnfkov.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":431,"height":772};
const content = `<path class="fu4lnfkov"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:s-upper-case" /></template>
