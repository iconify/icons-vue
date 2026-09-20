<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/q/qj8ii1bcd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="qj8ii1bcd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="majesticons:presentation" /></template>
