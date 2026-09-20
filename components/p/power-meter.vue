<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lpvwby7ij.css';
import '../../css/h/h1qw7gi7h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":15,"height":15};
const content = `<path class="lpvwby7ij"/><path class="h1qw7gi7h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="temaki:power-meter" /></template>
