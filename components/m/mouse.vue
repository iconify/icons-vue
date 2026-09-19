<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xk-i8_1pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":705,"height":1024};
const content = `<path class="xk-i8_1pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:mouse" /></template>
