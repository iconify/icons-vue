<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qz1of_bkk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":8,"height":8};
const content = `<path class="qz1of_bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="picon:stop" /></template>
