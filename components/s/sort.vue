<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/thv0p7btk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":21,"height":21};
const content = `<path class="thv0p7btk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="system-uicons:sort" /></template>
