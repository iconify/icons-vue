<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/twolibc3v.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="twolibc3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:star-fill" /></template>
