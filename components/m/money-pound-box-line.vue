<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/chcamsw5h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="chcamsw5h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ri:money-pound-box-line" /></template>
