<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pb1xtlv4b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":56,"height":56};
const content = `<path class="pb1xtlv4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="f7:sunrise-fill" /></template>
