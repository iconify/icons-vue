<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/dvc0w3uso.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="dvc0w3uso"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-flex:scanner-bar-code-remix" /></template>
