<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ebd8ltm4m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1792,"height":1792};
const content = `<path class="ebd8ltm4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa:qq" /></template>
