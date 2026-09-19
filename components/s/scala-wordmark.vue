<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/x4vvvyndn.css';
import '../../css/l/lrvq4dd-h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="x4vvvyndn"/><path class="lrvq4dd-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:scala-wordmark" /></template>
