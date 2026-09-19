<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f_e_osbro.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<path class="f_e_osbro"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa6-solid:transgender" /></template>
