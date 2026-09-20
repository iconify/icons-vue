<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vi1s_1bil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="vi1s_1bil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:signal-strength-7" /></template>
