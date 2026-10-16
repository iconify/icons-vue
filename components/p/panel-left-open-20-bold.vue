<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/i00v-b3kp.css';
import '../../css/x/xehdjeb4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="i00v-b3kp"/><path class="xehdjeb4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="energy-icons:panel-left-open-20-bold" /></template>
