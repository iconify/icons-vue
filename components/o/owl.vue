<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g8ot9_brk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g8ot9_brk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:owl" /></template>
