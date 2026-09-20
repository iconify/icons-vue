<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/b/bj_2p5drs.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1568,"height":1568};
const content = `<path class="bj_2p5drs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="thesvg:maybank" /></template>
