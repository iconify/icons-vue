<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m8mtlxpmv.css';
import '../../css/a/a-zj5lbdq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="m8mtlxpmv"/><path class="a-zj5lbdq b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:spyder-wordmark" /></template>
