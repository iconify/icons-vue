<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/q0-2kjb3e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="q0-2kjb3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:square-arrow-up-on-square" /></template>
