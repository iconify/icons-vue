<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w1p6d7jyb.css';
import '../../css/x/xiad0yblv.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w1p6d7jyb"/><path class="xiad0yblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:text-cursor-input-filled" /></template>
