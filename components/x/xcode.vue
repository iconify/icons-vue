<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kksrbfb_x.css';
import '../../css/x/xa3ht-bbv.css';
import '../../css/j/j3u72_b5w.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="kksrbfb_x"/><path class="xa3ht-bbv"/><path class="j3u72_b5w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:xcode" /></template>
