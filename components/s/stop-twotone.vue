<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckq9ugjzq.css';
import '../../css/e/eadgts_vo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ckq9ugjzq"/><path class="eadgts_vo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ant-design:stop-twotone" /></template>
