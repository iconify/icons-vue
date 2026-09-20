<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x6ec4gd1f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="x6ec4gd1f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:signal-strength-2" /></template>
