<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/upr5s1btc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="upr5s1btc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:progress-0" /></template>
