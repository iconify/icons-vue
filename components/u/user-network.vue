<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/z/z8e9bvbzx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="z8e9bvbzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:user-network" /></template>
