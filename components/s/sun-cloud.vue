<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qqqiq4boj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="qqqiq4boj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ix:sun-cloud" /></template>
