<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zxu4mccbq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1000,"height":1000};
const content = `<path class="zxu4mccbq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="websymbol:progress-5" /></template>
