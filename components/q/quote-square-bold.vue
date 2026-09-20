<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/t/tvm_01f-a.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tvm_01f-a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:quote-square-bold" /></template>
