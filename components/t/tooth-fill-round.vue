<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/l/lxu6oxjbm.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lxu6oxjbm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tooth-fill-round" /></template>
