<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/g/gf1tzwukj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gf1tzwukj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-exclamation-point-filled" /></template>
