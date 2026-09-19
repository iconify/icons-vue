<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kr9fsfb8t.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":2048,"height":1792};
const content = `<path class="kr9fsfb8t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:window-restore" /></template>
