<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/u/urath4yqn.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="urath4yqn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fe:search" /></template>
