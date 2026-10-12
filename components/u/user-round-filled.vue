<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/r/rv_ma3j-p.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rv_ma3j-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-round-filled" /></template>
