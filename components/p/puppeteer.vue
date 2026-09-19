<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/o/ozeyqcctf.css';
import '../../css/p/paymb2lad.css';
import '../../css/f/fmnfphbvx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ozeyqcctf"/><path class="paymb2lad"/><path class="fmnfphbvx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="catppuccin:puppeteer" /></template>
