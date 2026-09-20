<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/mo56o1kxh.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mo56o1kxh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="mingcute:user-hide-fill" /></template>
