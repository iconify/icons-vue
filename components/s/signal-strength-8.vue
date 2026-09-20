<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/goppj6bth.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="goppj6bth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:signal-strength-8" /></template>
