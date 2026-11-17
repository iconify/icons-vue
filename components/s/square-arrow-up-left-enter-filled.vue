<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w9_asgiqp.css';
import '../../css/l/lznavzkfz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w9_asgiqp"/><path class="lznavzkfz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:square-arrow-up-left-enter-filled" /></template>
