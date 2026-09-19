<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xx85bbbhz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":384,"height":512};
const content = `<path class="xx85bbbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:walkie-talkie" /></template>
