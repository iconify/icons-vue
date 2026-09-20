<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/c/c2lchr8db.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="c2lchr8db"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-freehand:saving-bag-increase" /></template>
