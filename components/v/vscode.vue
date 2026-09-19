<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qjl-c0ezu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="qjl-c0ezu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vscode" /></template>
