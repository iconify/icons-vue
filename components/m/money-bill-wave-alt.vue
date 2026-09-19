<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/ulyc9jzzv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="ulyc9jzzv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:money-bill-wave-alt" /></template>
