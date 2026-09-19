<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t14b_mbbi.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="t14b_mbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:music-albums-fill" /></template>
