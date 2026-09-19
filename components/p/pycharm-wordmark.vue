<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/g128-w4ww.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="g128-w4ww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="devicon-plain:pycharm-wordmark" /></template>
