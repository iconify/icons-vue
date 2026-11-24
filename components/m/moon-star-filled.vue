<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/uw1jalb_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uw1jalb_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="lucide-extended:moon-star-filled" /></template>
