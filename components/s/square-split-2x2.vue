<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mq6mer8bc.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="mq6mer8bc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-split-2x2" /></template>
