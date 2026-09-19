<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t1v5_pbko.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":1024,"height":1025};
const content = `<path class="t1v5_pbko"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="whh:missedcall" /></template>
