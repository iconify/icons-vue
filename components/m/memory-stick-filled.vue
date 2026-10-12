<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs-7ct1jj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="hs-7ct1jj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:memory-stick-filled" /></template>
