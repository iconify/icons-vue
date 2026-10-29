<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f6avd7p5r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6avd7p5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:microwave-solid" /></template>
