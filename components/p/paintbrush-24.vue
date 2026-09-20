<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/ntt91gjof.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ntt91gjof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="octicon:paintbrush-24" /></template>
