<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xxbwb-ipt.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="xxbwb-ipt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:truck" /></template>
