<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xc_2pfb3v.css';
import '../../css/z/zz8dk9k1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="xc_2pfb3v"/><path class="zz8dk9k1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-icon-theme:objective-cpp" /></template>
