<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/j/jk1_f629e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk1_f629e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:ungroup-filled" /></template>
