<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iqh5eqr2x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="iqh5eqr2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:today" /></template>
