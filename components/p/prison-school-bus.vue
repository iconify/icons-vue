<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yv8thob0o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":448};
const content = `<path class="yv8thob0o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ps:prison-school-bus" /></template>
