<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/js7pf5byf.css';
import '../../css/i/iv3gg9_op.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="js7pf5byf"/><path class="iv3gg9_op"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:tailwindcss-wordmark" /></template>
