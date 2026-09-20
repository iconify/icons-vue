<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/y7b8dez1j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="y7b8dez1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:square-arrow-down-right-fill" /></template>
