<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/joehf8bxi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="joehf8bxi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:unlock" /></template>
