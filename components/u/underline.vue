<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/h/hs8trmb5x.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hs8trmb5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:underline" /></template>
