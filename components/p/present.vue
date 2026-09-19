<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/oi4280bdv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":628,"height":717};
const content = `<path class="oi4280bdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:present" /></template>
