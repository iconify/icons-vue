<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c_2q7uzrl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="c_2q7uzrl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:quote-bubble-fill" /></template>
