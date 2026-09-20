<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i6hb5h4da.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="i6hb5h4da"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:plus" /></template>
