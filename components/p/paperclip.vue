<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9qwb5mqe.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="w9qwb5mqe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:paperclip" /></template>
