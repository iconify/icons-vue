<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/n/neohn4bis.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="neohn4bis"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:volume-control-up-1" /></template>
