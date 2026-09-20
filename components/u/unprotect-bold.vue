<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/m/ma33lmbkx.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ma33lmbkx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="streamline-ultimate:unprotect-bold" /></template>
