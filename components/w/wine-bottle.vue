<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x_89rtb6l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x_89rtb6l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:wine-bottle" /></template>
