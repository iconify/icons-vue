<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/progeegpm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="progeegpm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoir:phone-minus-solid" /></template>
