<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/a/alm8q0_fd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="alm8q0_fd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="heroicons-solid:receipt-tax" /></template>
