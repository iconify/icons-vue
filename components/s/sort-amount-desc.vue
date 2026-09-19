<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fe1v0h6hk.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":640,"height":640};
const content = `<path class="fe1v0h6hk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fa7-solid:sort-amount-desc" /></template>
