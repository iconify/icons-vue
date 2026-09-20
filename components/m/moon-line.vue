<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/da-21i6_l.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="da-21i6_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:moon-line" /></template>
