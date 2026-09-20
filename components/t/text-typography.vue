<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/clfsm8btx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="clfsm8btx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="proicons:text-typography" /></template>
