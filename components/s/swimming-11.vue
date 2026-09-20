<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qfr4dsb0p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":11,"height":11};
const content = `<path class="qfr4dsb0p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="maki:swimming-11" /></template>
