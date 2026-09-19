<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xf40h41pm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="xf40h41pm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:person-falling" /></template>
