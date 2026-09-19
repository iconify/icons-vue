<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wz3p94bgn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wz3p94bgn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:terraform" /></template>
