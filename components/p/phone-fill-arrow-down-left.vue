<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qc54upbzb.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="qc54upbzb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-fill-arrow-down-left" /></template>
