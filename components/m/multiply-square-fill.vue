<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lx4oct3hz.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lx4oct3hz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mage:multiply-square-fill" /></template>
