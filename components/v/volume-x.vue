<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/ij30-_bnk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ij30-_bnk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="feather:volume-x" /></template>
