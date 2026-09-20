<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/f/fh3e_4i8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fh3e_4i8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:remove-format" /></template>
