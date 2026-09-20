<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vs2yn_btv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="vs2yn_btv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:venus-solid" /></template>
