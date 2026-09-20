<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w7l5kub7j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="w7l5kub7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="quill:mail-unsub" /></template>
