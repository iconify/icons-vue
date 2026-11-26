<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xru9etm2q.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="xru9etm2q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:rstan" /></template>
