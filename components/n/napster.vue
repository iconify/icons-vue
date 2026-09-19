<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l64tr8bru.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":496,"height":512};
const content = `<path class="l64tr8bru"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:napster" /></template>
