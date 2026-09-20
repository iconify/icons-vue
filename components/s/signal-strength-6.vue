<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/a3rhadh4k.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="a3rhadh4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:signal-strength-6" /></template>
