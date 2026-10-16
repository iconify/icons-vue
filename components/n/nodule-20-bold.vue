<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t8pk9obri.css';
import '../../css/e/eepyewbvn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="t8pk9obri"/><path class="eepyewbvn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:nodule-20-bold" /></template>
