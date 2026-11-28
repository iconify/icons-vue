<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/y/yidn5ubil.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yidn5ubil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noviair-light:salad" /></template>
