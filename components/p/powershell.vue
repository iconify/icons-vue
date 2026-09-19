<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/imkjc5bcb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="imkjc5bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cib:powershell" /></template>
