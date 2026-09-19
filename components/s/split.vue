<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zqbwznbuj.css';
import '../../css/w/wg_xn1bwc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="zqbwznbuj"/><path class="wg_xn1bwc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:split" /></template>
