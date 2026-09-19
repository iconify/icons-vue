<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/la20gcqdw.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="la20gcqdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="akar-icons:scissor" /></template>
