<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/udao9qkrj.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="udao9qkrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:wrench" /></template>
