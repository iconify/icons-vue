<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hwosufbcj.css';
import '../../css/r/re3b6ubpp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hwosufbcj"/><path class="re3b6ubpp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:soup-filled" /></template>
