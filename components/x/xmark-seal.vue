<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/zin4mvb-r.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="zin4mvb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:xmark-seal" /></template>
