<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kd0b72b5u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kd0b72b5u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:spoon" /></template>
