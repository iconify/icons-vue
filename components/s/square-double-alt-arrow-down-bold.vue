<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/p/pqapcub6j.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pqapcub6j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:square-double-alt-arrow-down-bold" /></template>
