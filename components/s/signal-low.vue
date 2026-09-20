<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t5ygh_b1u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="t5ygh_b1u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:signal-low" /></template>
