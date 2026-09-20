<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/ckgc0n10h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ckgc0n10h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="la:spa" /></template>
