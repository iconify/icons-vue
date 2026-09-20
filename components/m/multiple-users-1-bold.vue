<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/w/w2_ykwjfd.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w2_ykwjfd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:multiple-users-1-bold" /></template>
