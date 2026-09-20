<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/f1-3t0ibm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f1-3t0ibm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="simple-icons:mui" /></template>
