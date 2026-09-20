<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nqhngccyu.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nqhngccyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mdi:wifi-strength-4-lock-open" /></template>
