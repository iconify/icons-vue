<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zh95h3b6d.css';
import '../../css/g/g1w9e8beh.css';
import '../../css/y/yp8fbucri.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zh95h3b6d"/><path class="g1w9e8beh"/><path class="yp8fbucri"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon:thymeleaf" /></template>
