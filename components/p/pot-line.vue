<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/e/ew3ta5bdf.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ew3ta5bdf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:pot-line" /></template>
