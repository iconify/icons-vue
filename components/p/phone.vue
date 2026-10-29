<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/muqvk_xvm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="muqvk_xvm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="withicons:phone" /></template>
