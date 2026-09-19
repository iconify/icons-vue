<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/i/iyy0xcbbr.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="iyy0xcbbr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="griddy-icons:shopping-basket-check" /></template>
