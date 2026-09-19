<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/k/km3x3cedu.css';
import '../../css/c/c_pfbfb0h.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="km3x3cedu"/><path clip-rule="evenodd" class="c_pfbfb0h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="cuida:rendo-outline" /></template>
