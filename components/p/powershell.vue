<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oa5kl5bks.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oa5kl5bks"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:powershell" /></template>
