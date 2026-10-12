<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zt1b-ybwl.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zt1b-ybwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="andrsrxn:wave-sawtooth" /></template>
