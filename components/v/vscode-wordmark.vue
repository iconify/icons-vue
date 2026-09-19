<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/sbr94kb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path clip-rule="evenodd" class="sbr94kb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vscode-wordmark" /></template>
