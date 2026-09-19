<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qgjs0nvgu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":512};
const content = `<path class="qgjs0nvgu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:user-slash" /></template>
