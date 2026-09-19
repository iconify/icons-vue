<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qd6xqqbei.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qd6xqqbei"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="entypo:squared-cross" /></template>
