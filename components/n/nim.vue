<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/l5bnq-jir.css';
import '../../css/j/j1uc_7b3b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="l5bnq-jir"/><path class="j1uc_7b3b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nim" /></template>
