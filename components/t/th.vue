<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/kp08k5b1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="kp08k5b1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa-solid:th" /></template>
