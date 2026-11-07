<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/d/d0sxd4ipq.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="d0sxd4ipq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:streets-navigation-outline" /></template>
