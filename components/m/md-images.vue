<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/we9xjz3rp.css';
import '../../css/g/g2vc8actl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="we9xjz3rp"/><path class="g2vc8actl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:md-images" /></template>
