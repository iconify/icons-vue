<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/x/xa1ckxblo.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa1ckxblo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:star" /></template>
