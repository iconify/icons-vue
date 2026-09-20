<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/s/s2ub43w-o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="s2ub43w-o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:pill" /></template>
