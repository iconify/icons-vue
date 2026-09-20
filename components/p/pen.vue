<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z2eymdawd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="z2eymdawd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:pen" /></template>
