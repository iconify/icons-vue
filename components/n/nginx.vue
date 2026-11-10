<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xqutpcb2e.css';
import '../../css/i/itzswk0_f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xqutpcb2e"/><path class="itzswk0_f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nginx" /></template>
