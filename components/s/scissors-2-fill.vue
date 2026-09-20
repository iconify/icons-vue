<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/myha_s0_i.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="myha_s0_i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:scissors-2-fill" /></template>
