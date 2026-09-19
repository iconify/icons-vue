<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gijyo05ck.css';
import '../../css/l/l0-cexb8m.css';
import '../../css/a/a1k_o6b_u.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="gijyo05ck"/><path class="l0-cexb8m"/><path class="a1k_o6b_u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:nim-wordmark" /></template>
