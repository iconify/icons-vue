<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/v33sube9b.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v33sube9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="eos-icons:modified-date" /></template>
