<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/ho1q24m-f.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="ho1q24m-f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:people-carry-box" /></template>
