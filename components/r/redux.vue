<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xeae1zb8m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xeae1zb8m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:redux" /></template>
