<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nxhm1j33d.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="nxhm1j33d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="at-icons:text-input" /></template>
