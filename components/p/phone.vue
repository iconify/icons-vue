<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/n_lnmcbbv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="n_lnmcbbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="icons8:phone" /></template>
