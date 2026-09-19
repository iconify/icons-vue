<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/edsj9em_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1200,"height":1200};
const content = `<path class="edsj9em_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="el:repeat-alt" /></template>
