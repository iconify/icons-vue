<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/egumi9b1d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="egumi9b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:p-and-i-symbols" /></template>
