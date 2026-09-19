<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q_dd5e65m.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="q_dd5e65m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:titaniumsdk" /></template>
