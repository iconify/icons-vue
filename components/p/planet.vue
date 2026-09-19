<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xj5lm6beb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xj5lm6beb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="famicons:planet" /></template>
