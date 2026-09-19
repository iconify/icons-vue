<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/nducsjboj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="nducsjboj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:phone-fill-badge-plus" /></template>
