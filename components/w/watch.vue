<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zyzqfc13x.css';
import '../../css/e/e_0e-zbty.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<rect class="zyzqfc13x"/><path class="e_0e-zbty"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ion:watch" /></template>
