<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/m4wmcmron.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="m4wmcmron"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:rotate-right" /></template>
