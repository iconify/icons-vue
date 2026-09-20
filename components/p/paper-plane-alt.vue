<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/r2q2m8bvc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="r2q2m8bvc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:paper-plane-alt" /></template>
