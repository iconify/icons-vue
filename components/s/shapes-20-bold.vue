<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l1gs6kbwk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="l1gs6kbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:shapes-20-bold" /></template>
