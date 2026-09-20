<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/e_q4bkngh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="e_q4bkngh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:vscode-32" /></template>
