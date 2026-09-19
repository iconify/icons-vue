<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lb4yqob1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":769,"height":690};
const content = `<path class="lb4yqob1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ls:palette" /></template>
