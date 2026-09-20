<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mr-5j_b8e.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mr-5j_b8e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:textbox-minus-line" /></template>
