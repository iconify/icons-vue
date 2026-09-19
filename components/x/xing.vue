<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/o-n64rb1o.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="o-n64rb1o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-brands:xing" /></template>
