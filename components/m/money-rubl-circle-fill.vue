<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yow4obkue.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="yow4obkue"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:money-rubl-circle-fill" /></template>
