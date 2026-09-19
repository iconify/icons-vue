<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g6b-56b1l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g6b-56b1l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cbi:sinclair" /></template>
