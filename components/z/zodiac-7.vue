<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zukfnb_jc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":14,"height":14};
const content = `<path class="zukfnb_jc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline:zodiac-7" /></template>
