<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/wcnuh7clv.css';
import '../../css/y/y3s_gsbxm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="wcnuh7clv"/><path class="y3s_gsbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:thealgorithms-wordmark" /></template>
