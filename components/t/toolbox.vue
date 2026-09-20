<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i0ay6jbyx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="i0ay6jbyx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:toolbox" /></template>
