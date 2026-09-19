<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zj_9l9bai.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="zj_9l9bai"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:vertx" /></template>
