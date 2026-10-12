<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/t0vebbm1i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t0vebbm1i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:user-minus-filled" /></template>
