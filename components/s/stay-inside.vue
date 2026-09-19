<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/io1ow38wk.css';
import '../../css/g/g21o-jbgm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="io1ow38wk"/><path class="g21o-jbgm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="carbon:stay-inside" /></template>
