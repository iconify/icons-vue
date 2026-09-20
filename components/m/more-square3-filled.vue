<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckv1mmfoq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ckv1mmfoq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="reicon:more-square3-filled" /></template>
